# CMSAFE
 Python notebooks for data elaboration

Correnti di Bias in condizioni di default.

Considero la corrente I_LDAC. Essa gestisce il range dinamico del Trimming DAC.


Test di calibrazione dei preamp con soglia a 1000 elettroni (mean ~ 520) per:

V_drop_target ~ 44.8 mV		I_LDAC ~ 8.0 uA		mean = 520.102	sigma = 0.949
	
V_drop_target ~ 70 mV 		I_LDAC ~ 12.5 uA	mean = 520.997	sigma = 0.588
V_drop_target ~ 72.8 mV		I_LDAC ~ 13.0 uA  	mean = 520.409 	sigma = 0.577
V_drop_target ~ 75.6 mV		I_LDAC ~ 13.5 uA	mean = 519.606	sigma = 0.568

V_drop_target ~ 100.8 mV	I_LDAC ~ 18.0 uA	mean = 520.454	sigma = 0.674

I valori di tensione di V_drop_target sono letti dai Test Point TP16 - TP17

I file di calibrazione nella cartella CMSAFE_calibs contengono le configurazioni esportate dal sw CMSAFE_VthCalibration