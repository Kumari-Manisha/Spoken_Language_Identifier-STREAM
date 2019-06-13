**STREAM (Smart Translation Enabling and Aiding Multi-cultral populations)**

**Description:**

In cases where non-English speakers, typically refugees or 'newcomers' to the region, seek medical care, health care staff members must quickly identify the patient's language so that the appropriate interpreter can be called.
The goal of this project is to streamline or shorten the time for the intake processes for non-English speaking patients(specially Nepali and non-Nepali) and their families by developing a digital language identification tool for health care providers and first responders.

**Dataset (complete):**

**Nepali Data:**

	115 audio files (10 – 40 mins) , 2.42 GB(Zip)
	Splitted to 11,424 files (10 Sec), 19.4 GB

**Other Language Data:**

	From Topcoder:78,496 files, 5.5 GB(Zip)
	Non Nepali Data of 10 sec each
  176 Languages
	Each language has 446 sample files


**Dataset (sample):**

Training dataset: 2069 audio files 
Test Dataset: 398 files 

**Feature Extraction:**
  used **MFCC**. 
  The **Mel-Frequency Cepstral Coefficients (MFCC)** features is the most commonly used features in speaker recognition. It combines the 	   advantages of the cepstrum analysis with a perceptual frequency scale based on critical bands.
  
	* MFCC is based on human hearing perceptions which cannot perceive frequencies over 1Khz.
	
	* In other words, in MFCC is based on known variation of the human ear’s critical bandwidth with frequency. 
	
	* MFCC has two types of filter which are spaced linearly at low frequency below 1000 Hz and logarithmic spacing above 1000Hz.
 

**Models based on the sample data and their accuracy score:**

	* The artificial neural network-  90 %

	*  Decision tree- 90%

 	*  Random Forest- 86%

	*  SVM-  100%
