 <div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-abyannash-400073194/)



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h2 align="center">Fake News Detection using Passive Aggressive Classifier</h3>

  <p align="center">
    Utilizing Passive Aggressive Classifier to identify fake news
    <br /><br />
    <a href = https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view>dataset here</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#dataset-splitting-and-tfidvectorizer-initialization">Dataset Splitting and TfidVectorizer initialization</a></li>
    <li><a href="#model-training-and-model-results">Model Training and Model Results</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The is is a simple project utilizing Passive Aggressive Classifier to identify fake news. My main objective was to learn the function and text vectorization by applying the functions in a model.

<p align="right">(<a href="#top">back to top</a>)</p>


## Dataset

For this dataset the distribution was 50/50 between REAL and FAKE. After checking, the downloaded dataset is clean. <br/><br/>
![image](https://user-images.githubusercontent.com/29911769/163936446-c506a83b-29dd-46dc-bb02-31983d900780.png)


<p align="right">(<a href="#top">back to top</a>)</p>


## Dataset Splitting and TfidVectorizer Initialization

TfidVectorizer converts a collection of raw documents to a matrix of TF-IDF features. Stop words are words like “and”, “the”, “him”, which are presumed to be uninformative in representing the content of a text, and which may be removed to avoid them being construed as signal for prediction. <br/><br/>

![image](https://user-images.githubusercontent.com/29911769/163940459-be845794-5108-4e15-9d6e-3c0ddf34bb21.png)


<p align="right">(<a href="#top">back to top</a>)</p>

## Model Training and Model Results
PassiveAggressiveScaler's algorithm remains passive for a correct classification outcome, and turns aggressive in the when there's a miscalculation. The algorithm then updates and adjusts.


![image](https://user-images.githubusercontent.com/29911769/163940753-0cfd68d0-eef6-4cec-a38e-1eecc2be0dba.png)

After training the model we achieved a relatively good accuracy of 93%
<p align="right">(<a href="#top">back to top</a>)</p>


## Contact

Mohammed Abyannash - mohammedabyan22@gmail.com

Project Link: [https://github.com/mohammedabyan/fakeNewsDetection](https://github.com/mohammedabyan/fakeNewsDetection)

<p align="right">(<a href="#top">back to top</a>)</p>


