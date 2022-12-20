# Dimensionality-Reductions


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project implement different tasks to reduce the dimensionality of the character image data, visualize the components and compare the performance and speed between original and reduced dataset.

The dataset is collected by students of [Dr. Catia Silva](https://faculty.eng.ufl.edu/catia-silva/bio/) in `2022 Spring Fund of Machine Learning` in [University of Florida](https://www.ufl.edu/).
This dataset includes 9600 character with 90000 features in each image, 10 classes of character is presented in the following:

```
**a**     **b**     **c**     **d**     **e**     **f**     **g**     **h**     **$**     **#**
```
All alphabet include both higher and lower cases.

The data was downsampled, visualized, preprocessed, dimensionality reduced and used to train several classification model. The data was already split into 70:30.

After implementing performance evaluation metrics, we get 76% for train set and 36% for test set in original dataset and 51% for train set and 41% for test set in reduced dataset (using `PCA`) with logistic regression. Training time for original dataset is 81.75 seconds and 4.84 seconds for reduced dataset.
As for the data dimensionanlly reduced by manifold learning algorithms `MDS`, `iSOMAP` and `LLE`, we get accuracy 11.7%, 16.7%, 10.35% and number of components 6, 17, 8, respectively for test set.


For more detail, please see my report paper. [https://github.com/Danielyaoan/Dimensionality-Reductions.git](https://github.com/Danielyaoan/Dimensionality-Reductions.git)


<!-- GETTING STARTED -->
## Getting Started


### Dependencies

* NumPy

```sh
pip install numpy
```
* Pandas

```sh
pip install pandas
```

* scikit_learn
```sh
pip install scikit-learn
```

* MatPlotLib
```sh
pip install matplotlib
```


* Scipy
```sh
pip install Scipy
```

* joblib
```sh
pip install joblib
```


* time
```sh
pip install time
```

* warnings
```sh
pip install warnings
```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Danielyaoan/Dimensionality-Reductions.git
   ```
2. Original, downsampled data and model for problem 2 & 4 can be found in google cloud 

   [https://drive.google.com/drive/folders/1ouE7LUHSCHVRzqHTGCm2SlGwhBsWHa8d?usp=sharing](https://drive.google.com/drive/folders/1ouE7LUHSCHVRzqHTGCm2SlGwhBsWHa8d?usp=sharing)



<!-- USAGE EXAMPLES -->
## Usage

Run the Train notebook once so it can automatically generate the file for model and dataset for each task. The Test notebook calls all necessary trained pipelines to evaluate performance and present transformation in the test set.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Yao An Lee - danielyaoanlee@gmail.com

Project Link: [https://github.com/Danielyaoan/Dimensionality-Reductions.git](https://github.com/Danielyaoan/Dimensionality-Reductions.git)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements



## Thank you
