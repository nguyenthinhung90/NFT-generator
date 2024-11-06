# NFT generator

this is the easiest way to generate a hell lotta image

buckle up and follow me!

## how to

first have your image in .png (transparent background of course!)

structure it in this way. in a folder create a sub-folder for each part of your NFT. layer will be sorted based on name.
for simplicity I would recommend `[layer no]_whatever`
then in each sub-folder just put our part options in there.

for example.

```
your_awesome_nft
├── 01_body
│   ├── body_1.png
│   └── body_2.png
└── 02_face
    ├── face_1.png
    └── face_2.png
```

ok all good?

find a way to set up python [link](https://realpython.com/installing-python/)

run this stuff (don't worry I'm not gonna hack you LOL)

```
pip install -r requirement.txt
py generate.py [input_dir] [output_dir] [how many do ya want]
```

## advance feature

### option flag

`--unique` generate unique combination only. however it will not be random. (will generate in predictable sequence) 

### animation

`--animate` to activate feature

`--fps` for fps default 4

`--n_frame` to specify no of frame you have. for now each part can be either static or animate, if animate each option
must have `n_frame` in each folder

the folder structure will be similar to normal one. but in each option you can have a sub-folder instate of a png.

```
stick_man_part
├── 1_bg
│   ├── bg_1.png
│   └── bg_2.png
└── 2_animate_part
    ├── option1
    │   ├── frame_1.png
    │   └── frame_2.png
    └── count_th
        ├── frame_1.png
        └── frame_2.png
```

### GUI

```
pip3 install -r requirement_gui.txt
streamlit run nft-generator-gui.py 
```

and just follow the gui

### MISC

my [FB](https://www.facebook.com/yoyoismee/) <- can talk to me, shill, or request new feature here.

buy me coffee at `yoyoismee.eth` or `0x6647a7858a0B3846AbD5511e7b797Fc0a0c63a4b`

(actually I might just use it to buy more NFT lol) 
print('nzdbd')