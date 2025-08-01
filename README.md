# 🖼️ Image Inpainting for Irregular Holes Using Partial Convolutions

## 💻 Tech stack
The application is built completely in [Python](https://www.python.org/). I have created [Jupyter Notebooks](https://jupyter.org/) on [Google Colab](https://colab.research.google.com/) to train the model and the desktop app is built using [PyQt5](https://pypi.org/project/PyQt5/) 🐍

## Results

| Masked Image  | Result  | Ground Truth  |
|---|---|---|
| ![unnamed](https://user-images.githubusercontent.com/41234408/114698170-669b8980-9d3c-11eb-91e3-3425a42afd4b.png)  | ![unnamed (1)](https://user-images.githubusercontent.com/41234408/114698177-68fde380-9d3c-11eb-9303-b3d46cf51e23.png)  | ![unnamed (2)](https://user-images.githubusercontent.com/41234408/114698181-69967a00-9d3c-11eb-8264-8cce112df539.png)  |
| ![11](https://user-images.githubusercontent.com/41234408/114698276-8c289300-9d3c-11eb-9c05-d2a4cc49a6b1.png)  | ![12](https://user-images.githubusercontent.com/41234408/114698279-8e8aed00-9d3c-11eb-879b-e54a8eba9d53.png)  | ![13](https://user-images.githubusercontent.com/41234408/114698286-8fbc1a00-9d3c-11eb-9c67-712bc618dab4.png)  |
| ![21](https://user-images.githubusercontent.com/41234408/114698380-acf0e880-9d3c-11eb-8529-ad5699e465ac.png)  | ![22](https://user-images.githubusercontent.com/41234408/114698389-aebaac00-9d3c-11eb-9a7b-fae601ec017d.png)  | ![23](https://user-images.githubusercontent.com/41234408/114698398-b11d0600-9d3c-11eb-95d6-2a291afbb216.png)  |
| ![31](https://user-images.githubusercontent.com/41234408/114698957-520bc100-9d3d-11eb-819d-dd60740553a2.png)  | ![32](https://user-images.githubusercontent.com/41234408/114698962-533cee00-9d3d-11eb-8bf6-9306ec730948.png)  | ![33](https://user-images.githubusercontent.com/41234408/114698964-546e1b00-9d3d-11eb-91fe-f4936018feea.png)  |
| ![41](https://user-images.githubusercontent.com/41234408/114699335-c9415500-9d3d-11eb-90f8-48e456b610ce.png)  | ![42](https://user-images.githubusercontent.com/41234408/114699338-cb0b1880-9d3d-11eb-9450-19babf530a98.png)  | ![43](https://user-images.githubusercontent.com/41234408/114699345-ccd4dc00-9d3d-11eb-9740-64062b492622.png)  |
| ![51](https://user-images.githubusercontent.com/41234408/114700317-04905380-9d3f-11eb-8adb-25fd77a92a19.png)  | ![52](https://user-images.githubusercontent.com/41234408/114700328-065a1700-9d3f-11eb-967d-a4e04d4dd1a6.png)  | ![53](https://user-images.githubusercontent.com/41234408/114700335-078b4400-9d3f-11eb-8f54-1b25ac494d1d.png)  |

## Desktop App

| ![4](https://user-images.githubusercontent.com/41234408/114700626-5d5fec00-9d3f-11eb-852a-5b7f7baa1cd7.png)  | ![3](https://user-images.githubusercontent.com/41234408/114700623-5cc75580-9d3f-11eb-9320-c59abc03cac7.png)  |
|---|---|
| ![1](https://user-images.githubusercontent.com/41234408/114700614-59cc6500-9d3f-11eb-9c2a-34ed7e3dca95.png)  | ![2](https://user-images.githubusercontent.com/41234408/114700619-5b962880-9d3f-11eb-96fb-612c8e3f956d.png)  |
| ![pasted image 1](https://user-images.githubusercontent.com/41234408/114700632-5f29af80-9d3f-11eb-8448-9b2ffeb2ec98.png)  | ![pasted image 0](https://user-images.githubusercontent.com/41234408/114700627-5df88280-9d3f-11eb-95e3-a5b15a8604b5.png)  |

## :hammer: Installation 

For setting up the desktop app, head over [here](https://gitlab.com/yashk2000/pconv-inpaintin/tree/master/application).

## 👨‍💻 How do I contribute?
- Before contributing do go through the [Code of Conduct](https://gitlab.com/yashk2000/pconv-inpainting/blob/master/CODE_OF_CONDUCT.md) :wrench:
- Please go through the [Contributing Guidelines](https://gitlab.com/yashk2000/pconv-inpainting/blob/master/CONTRIBUTING.md) as well. 📚
- If you find any bugs in the application, or a feature you think would be nice to have, please open an issue.❗

## 📈 Folder Struture 

Each folder has it's own dedicated readme on what it's contents do, how to set them up and use them. 

- [`InPainting Notebook`](https://gitlab.com/yashk2000/pconv-inpainting/tree/master/InPainting%20Notebook): This folder contains the jupyter notebook we trained on Google Colab. 
- [`application`](https://gitlab.com/yashk2000/pconv-inpainting/tree/master/application): This folder contains the main PyQt5 desktop application.  
- [`inpainting`](https://gitlab.com/yashk2000/pconv-inpainting/tree/master/inpainting): This folder contains python scripts that can be used for training a model, or making predictions. They can directly be imported into your own project. 

## 📜 License
This project is released under a free and open-source software license, Apache License 2.0 or later ([LICENSE](LICENSE) or https://www.apache.org/licenses/LICENSE-2.0). The documentation is also released under a free documentation license, namely the [GFDL v1.3](https://www.gnu.org/licenses/fdl-1.3.en.html) license or later.

### 🖊️ Contributions
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be licensed as above, without any additional terms or conditions.

## :books: Resources 

- "Image Inpainting for Irregular Holes Using Partial Convolutions", [https://arxiv.org/abs/1804.07723](https://arxiv.org/abs/1804.07723)

### Citation

```
@inproceedings{liu2018partialpadding,
   author    = {Guilin Liu and Kevin J. Shih and Ting-Chun Wang and Fitsum A. Reda and Karan Sapra and Zhiding Yu and Andrew Tao and Bryan Catanzaro},
   title     = {Partial Convolution based Padding},
   booktitle = {arXiv preprint arXiv:1811.11718},   
   year      = {2018},
}
```

```
@inproceedings{liu2018partialinpainting,
   author    = {Guilin Liu and Fitsum A. Reda and Kevin J. Shih and Ting-Chun Wang and Andrew Tao and Bryan Catanzaro},
   title     = {Image Inpainting for Irregular Holes Using Partial Convolutions},
   booktitle = {The European Conference on Computer Vision (ECCV)},   
   year      = {2018},
}
```
