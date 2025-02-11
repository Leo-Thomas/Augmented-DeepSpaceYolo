# Augmented-DeepSpaceYolo Dataset

![alt text](sample.png)

## About the project

This repository refers to the Augmented-DeepSpaceYolo dataset, which was used in the study [Deep Sky Object Detection in Astronomical Imagery Using YOLO Models: A Comparative Assessment](#). This dataset is an augmented version of the DeepSpaceYoloDataset, originally introduced in [DeepSpaceYoloDataset: Annotated Astronomical Images Captured with Smart Telescopes](https://www.mdpi.com/2306-5729/9/1/12), and is designed for deep sky object (DSO) detection, including nebulae, galaxies, and globular clusters.

## Data set description

The Augmented-DeepSpaceYolo dataset increases the number of images from the original 4,696 to 8,421 by applying data augmentation techniques. These transformations were carefully selected to simulate real-world variations encountered in astronomical imaging, enhancing model robustness and evaluation.

The following transformations were applied:

* **Cropping & zooming:** 0% minimum zoom, 20% maximum zoom
* **Rotations:** Between -15° and +15°
* **Brightness adjustments:** -15% to +15%
* **Blurring:** Up to 2.5 pixels
* **Noise addition:** Up to 0.15% of pixels

These augmentations reflect common challenges in astronomical observations:

* **Cropping & zooming** simulate variations in focal length and different perspectives.
* **Rotations** account for telescope movement and Earth’s rotation.
* **Brightness adjustments** replicate fluctuating light conditions and atmospheric interference.
* **Blurring** mimics slight defocusing and turbulence effects.
* **Noise addition** replicates sensor noise and other random artifacts affecting image quality.

A default split is provided, corresponding to the one used in the paper:

| Split        | # Images   |
|----------------|----------|
| Train       | 7,486   |
| Valid   | 469  |
| Test           | 466  |

The labels are provided in **YOLO format**, making them compatible with popular object detection frameworks. The images are in JPG format, with a resolution of 608×608 pixels.

## Download dataset

The dataset is available for download via Google Drive [here](https://drive.google.com/drive/folders/1HY_Xkc_tCFEVVOWdh_CSSgs5n_m1fGVb?usp=sharing).
<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CITAITON -->
## Citation

If you find this dataset useful, please cite the following article:

```
Soon

```
<!-- CONTACT -->
## Contact

**Leo Thomas Ramos**  
[LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - ltramos@cvc.uab.cat  
*Computer Vision Center, Universitat Autònoma de Barcelona, Spain*  

**Francklin Rivas-Echeverría**  
[LinkedIn](https://www.linkedin.com/in/francklin-rivas-echeverria-514180144/) - francklin.rivas@uta.edu  
*University of Texas at Arlington, USA*  


