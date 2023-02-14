<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center"><b>TS2IMG: Time Series to Image Classification</b></h3>

  <p align="center">
    TS2IMG is a project that uses Gramian Angular Field method to transform time series data into images, which are then classified using Convolutional Neural Networks (CNNs) and other deep learning approaches.
    <br />
  </p>
</div>


## Table of Contents
<!-- TABLE OF CONTENTS -->
<div align="center">
  <ul style="list-style: none;">
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#built-with">Built With</a></li>
    <li>
        <a href="#requirements">Requirements</a>
    </li>
    <li><a href="#experimental-results">Experimental Results</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ul>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/MetinUsta/Time-Series-To-Image-Classification)

This project explores the use of deep learning techniques for time series classification using images. The Gramian Angular Field method was used to convert time series data to images, allowing the application of image-based techniques to time series data. The UCI Human Activity Recognition Dataset was used for experimentation, which includes both raw signal data and statistical data extracted from the raw signal data.

Two methods were employed to combine the images generated from the time series data. The first method involved arranging the images in a 3x3 grid, while the second method involved stacking the images in the third axis. After all preprocessing steps were completed, Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks were trained on the dataset. Using more than one deep learning method allowed for comparison of the results.

This project aims to demonstrate the effectiveness of image-based techniques for time series classification and provides insight into the performance of different deep learning models.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Built With
[![TensorFlow][Tensorflow.org]][Tensorflow-url] [![Keras][Keras.io]][Keras-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Requirements

* Python
  ```sh
  numpy
  pandas
  pyts
  matplotlib
  tqdm
  tensorflow
  yaml
  attrdict
  ```

<!-- USAGE EXAMPLES -->
## Experimental Results

<table>
<thead>
  <tr>
    <th>Dataset</th>
    <th>Model</th>
    <th>Average Accuracy (%)</th>
    <th>Std. Dev. (pp*)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">Signal Data<br></td>
    <td>LSTM</td>
    <td>90.36</td>
    <td>1.48</td>
  </tr>
  <tr>
    <td>BiLSTM</td>
    <td>89.65</td>
    <td>2.57</td>
  </tr>
  <tr>
    <td>ConvLSTM</td>
    <td>90.38</td>
    <td>1.19</td>
  </tr>
  <tr>
    <td>Statistical Data</td>
    <td>BiLSTM</td>
    <td>85.37</td>
    <td>2.14</td>
  </tr>
  <tr>
    <td>Image Data (3X3 Grid)</td>
    <td>CNN</td>
    <td>79.02</td>
    <td>1.56</td>
  </tr>
  <tr>
    <td>Image Data (Stacked)</td>
    <td>CNN</td>
    <td>80.48</td>
    <td>1.12</td>
  </tr>
</tbody>
</table>

pp: Percentage Point

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contributors

Metin Usta - metin.usta01@hotmail.com

Mehmet Yiğit - 

Project Link: [https://github.com/MetinUsta/Time-Series-To-Image-Classification](https://github.com/MetinUsta/Time-Series-To-Image-Classification)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Pyts Documentation](https://pyts.readthedocs.io/en/stable/#)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: assets/tstoimage.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com

[Tensorflow.org]: https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white
[Tensorflow-url]: https://www.tensorflow.org/

[Keras.io]: https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white
[Keras-url]: https://keras.io/