# IMA traffic analysis source code

Given a pcap dataset, first extract flows, separate background traffic and merge the files using the scripts in /preprocess. 

/training/flow_df_functions.py contains base code that you can reference to build the models I used in the paper.
/training/*_ima.py are example scripts that analyze IMA traffic flows accordingly. 

Please cite the following papers for this research:

[*] Zolboo Erdenebaatar, Riyad Alshammari, Nur Zincir-Heywood, Marwa Elsayed, Bis Nandy, and Nabil Seddigh. Analyzing traffic characteristics of instant messaging applications on Android smartphones. In 2023 IEEE/IFIP Network Operations and Management Symposium (NOMS 2023), 2023.

[**] Zolboo Erdenebaatar, Riyad Alshammari, Nur Zincir-Heywood, Marwa Elsayed, Bis Nandy, and Nabil Seddigh. Instant messaging application encrypted traffic generation system. In 2023 IEEE/IFIP Network Operations and Management Symposium (NOMS 2023), 2023. 

Dataset from our research:

[***] Zolboo Erdenebaatar, Riyad Alshammari, Nur Zincir-Heywood, Marwa Elsayed, Biswajit Nandy, Nabil Seddigh, January 23, 2023, "Encrypted Mobile Instant Messaging Traffic Dataset", IEEE Dataport, doi: https://dx.doi.org/10.21227/aer2-kq52.
