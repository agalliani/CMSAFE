Correnti di Bias in condizioni di default.

Considero la corrente I_LDAC. Essa gestisce il range dinamico del Trimming DAC.


Test di calibrazione dei preamp con soglia a 1000 elettroni (mean ~ 520) per:

V_drop_target ~ 44.8 mV		I_LDAC ~ 8.0 uA		mean = 520.102	sigma = 0.949
	
V_drop_target ~ 70 mV 		I_LDAC ~ 12.5 uA	mean = 520.997	sigma = 0.588
V_drop_target ~ 72.8 mV		I_LDAC ~ 13.0 uA  	mean = 520.409 	sigma = 0.577
V_drop_target ~ 75.6 mV		I_LDAC ~ 13.5 uA	mean = 519.606	sigma = 0.568

V_drop_target ~ 100.8 mV	I_LDAC ~ 18.0 uA	mean = 520.454	sigma = 0.674

I valori di tensione di V_drop_target sono letti dai Test Point TP16 - TP17

Cartelle

calib_I_LDAC_12_5
calib_I_LDAC_13_0
calib_I_LDAC_13_5

contengono le configurazioni esportate dal sw CMSAFE_VthCalibration


//7/05

Provo con nuove misurazioni
	

V_drop_target ~	56 mV		I_LDAC ~ 10 uA		mean = 520.503	sigma = 0.665
V_drop_target ~	67.2 mV		I_LDAC ~ 12 uA		mean = 520.456	sigma = 0.519
V_drop_target ~ 78.4 mV		I_LDAC ~ 14 uA		mean = 520.241	sigma = 0.571
V_drop_target ~ 89.6 mV		I_LDAC ~ 16 uA		mean = 520.768	sigma = 1.56

V_drop_target ~ 112 mV		I_LDAC ~ 20.0 uA	mean = 518.978	sigma = 0.842





####################################################
Valuto il rumore con soglia 1500 elettroni a ILDAC ~ 14 uA in due casi:
- CD variabile 0 50 100 150 fF
- CD = 50 fF I_LKG_N crescente 0 5 10 15 20 nA