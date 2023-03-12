# Automatische-Segmentierung-des-Rechten-Ventrikels-auf-Kardio-MRT--Daten


Daten:
Die Daten stammen aus der MICCAI Challenge 2017:
• Website: https://www.creatis.insa-lyon.fr/Challenge/acdc/index.html
• Literatur: O. Bernard, A. Lalande, C. Zotti, F. Cervenansky, et al. "Deep Learning Techniques
for Automatic MRI Cardiac Multi-structures Segmentation and Diagnosis: Is the Problem
Solved ?" in IEEE Transactions on Medical Imaging, vol. 37, no. 11, pp. 2514-2525, Nov. 2018
- doi: 10.1109/TMI.2018.2837502
https://acdc.creatis.insa-lyon.fr/description/files/tmi_2018_bernard.pdf
• 100 3D+t SAX Cardio MRT-Daten entlang der Kurzen Achse (short axis =SAX)
• Manuell annotiert sind jeweils 3 Strukturen (Linker Ventrikel [blau], Rechter Ventrikel [rot] und
Myokard [grün]) auf zwei Zeitschritten: ED = Enddiastolischer und ES = Endsystolischer
Zeitschritt
• 5 verschiedene Gruppen, jew. 20 Patienten pro Gruppe: Normal, DCM, HCM, MINF, Abnormal RV
• Zuordnung:
o patient 1-20 with dilated cardiomyopathy (DCM);
o patient 21-40 with an hypertrophic cardiomyopathy (HCM);
o patient 41-60 with previous myocardial infarction (MINF);
o patient 61-80 healthy (NOR);
o patient 81-100 with abnormal right ventricle (RV)
