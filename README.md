# opentrons-balance
Supplementary information to the Opentrons application note on how to integrate a mass balance with the Opentrons OT-2 robot. 

There's a code `OT-2_BalanceCommunication` to connect and communicate with a Mettler Toledo (model #: MS303TS/00) precision balance. Before running this notebook, please install ensure your Python environment has the packages in `requirements.txt` installed. You can create a new virtual environemnt and then `pip install -r requirements.txt`. 

Additionally, three 3-d printing files & are presented in the `design-files` directory to produce a mass balance adapter as shown in the note. Finally, a technical drawing is also shown in this directory. This should be followed for cutting out slot #2 of the Opentrons deck where the mass balance will slot in. The end result should look as shown below.

![image](https://github.com/AniketChitre/opentrons-balance/assets/56798326/19a08bce-621e-47d2-8f16-87615909a4f7)
