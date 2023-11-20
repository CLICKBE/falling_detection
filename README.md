# Détection de chute

[FR]
L'objectif de ce projet était le développement d'un système de détection de chute des personnes. S'il détecte une chute, le système envoie un message d'alerte aux personnes, professionnels ou organisations concernés.

Ce projet est le résultat d'un travail collaboratif mené pendant le hackathon [impAct](https://le-click.be/impact/) par des personnes incroyables : Serra Bella, Antoine Van Malleghem, Mohamed El Amine Mokhtari and Mohamed Benkedadra.

La détection de chute est réalisée par caméra. Pour réaliser cette tâche, deux algorithmes ont été testés :
- YOLO
- une méthode basée sur la position des différents joints du squelette

[EN]
The objective of the falling detection project was to build a system that can detect people falls and send an alert message to relevant people, professional or organization.

This project is the result of the collaborative work led during [impAct](https://le-click.be/impact/) hackathon by amazing people : Serra Bella, Antoine Van Malleghem, Mohamed El Amine Mokhtari and Mohamed Benkedadra.

Two detection methods have been tested in this project : 
- the first one uses YOLO
- the second one is only based on the position of skeleton joints.

## impAct 2023
This project has been developped during [impAct 2023](https://le-click.be/impact/) hackhathon organized by [Le CLICK](https://le-click.be/).
This hackathon is a 2.5 days hackathon where, at least, one point of a responsible usage chart that was made for the hackathon needed to be addressed.
This 2023 edition focus was put on AI & XR.

## Use

1. Install requirements
```
git clone https://github.com/CLICKBE/falling_detection
cd falling_detection/
pip3 install -r requirements.txt
```

2. Get git submodules
```
git submodule update --init
```

3. Download weights
```
python3 config_env.py
```

4. Run
```
streamlit run app_v2.py
```

## CO2 Emission

[CodeCarbon](https://codecarbon.io/) python extension has been used in this project to compare gaz emission (or used power converted to gaz emission) of the two detection methods. 

- YOLO: 535g 
- Ours: 302g

![logo-impact](https://github.com/CLICKBE/falling_detection/assets/2494294/4d47cf9b-78c6-4bb8-9888-7c956681ebd9)

## Legal Notices
This work was produced as part of the FEDER Digistorm project, co-financed by the European Union and the Wallonia Region.

![Logo FEDER-FSE](https://www.enmieux.be/sites/default/files/assets/media-files/signatures/vignette_FEDER%2Bwallonie.png)

