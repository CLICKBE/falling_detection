# Falling detection

The objectives of the falling detection project was to build a system that can detect people falls and send an alert message to relevant people/professional/organization.
This project is the result of the collaborative concertation and construction of amazing people : Serra Bella, Antoine Van Malleghem, Mohamed El Amine Mokhtari and Mohamed Benkedadra.
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

