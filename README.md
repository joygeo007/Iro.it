### Project Title: Manga Colorizer Using TensorFlow and OpenCV

#### Project Description:
This project is a manga colorization tool that leverages deep learning techniques using TensorFlow and OpenCV. The primary goal of the project is to automatically colorize black-and-white manga images using trained models. This notebook demonstrates how to preprocess manga images, build and train neural networks, and generate colorized versions of the manga panels.

The project makes use of the [Manga109 dataset](http://www.manga109.org/en/download.html), a popular dataset for manga image research, which includes over 21,000 pages from 109 Japanese manga titles. This dataset serves as the foundation for training the model to understand and colorize manga-style artwork.

#### Features:
- Preprocessing of input manga images.
- Implementation of image colorization using TensorFlow and OpenCV.
- Visualization of colorized manga panels.
- Model training and evaluation.

#### Installation:
To run the notebook, ensure you have the following dependencies installed:
```bash
pip install tensorflow opencv-python matplotlib
```

#### Usage:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/manga-colorizer.git
    ```
2. Download the Manga109 dataset from [here](http://www.manga109.org/en/download.html) and place it in the appropriate folder.
3. Open the notebook `Iro_it_manga_colorizer.ipynb` and run the cells sequentially to process and colorize manga images.

#### Dataset:
The project utilizes the Manga109 dataset, which is available for research purposes. You can download the dataset from the [official website](http://www.manga109.org/en/download.html).

**Citations for Manga109 Dataset:**


```bibtex
@article{mtap_matsui_2017,
    author={Yusuke Matsui and Kota Ito and Yuji Aramaki and Azuma Fujimoto and Toru Ogawa and Toshihiko Yamasaki and Kiyoharu Aizawa},
    title={Sketch-based Manga Retrieval using Manga109 Dataset},
    journal={Multimedia Tools and Applications},
    volume={76},
    number={20},
    pages={21811--21838},
    doi={10.1007/s11042-016-4020-z},
    year={2017}
}

@article{multimedia_aizawa_2020,
    author={Kiyoharu Aizawa and Azuma Fujimoto and Atsushi Otsubo and Toru Ogawa and Yusuke Matsui and Koki Tsubota and Hikaru Ikuta},
    title={Building a Manga Dataset ``Manga109'' with Annotations for Multimedia Applications},
    journal={IEEE MultiMedia},
    volume={27},
    number={2},
    pages={8--18},
    doi={10.1109/mmul.2020.2987895},
    year={2020}
}
```

#### References:
- Manga109 Dataset: [Matsui et al., 2017](http://www.manga109.org/en/)
- TensorFlow Documentation: [https://www.tensorflow.org/](https://www.tensorflow.org/)
- OpenCV Documentation: [https://opencv.org/](https://opencv.org/)

#### Acknowledgments:
Special thanks to the creators of the Manga109 dataset for making this valuable resource available to the public. Their contributions have significantly advanced manga-related research and applications.
