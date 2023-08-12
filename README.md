<h1 align="center">Fashion MNIST Classification - Accuracy 92.1% </h1>
<div>
  <p align="center">
    This project is a convolutional neural network (CNN) built using PyTorch that classifies images from the Fashion-MNIST dataset. The network consists of several layers, including convolutional, pooling, and fully connected layers. The model achieved an accuracy of 92.1%
    <br/>
  </p>
</div>

<br/>
<div align="center">
  <a href="https://i.imgur.com/kjWVTBW.jpeg">
    <img src="https://i.imgur.com/kjWVTBW.jpeg" alt="Logo" width="860" height="444">
  </a>

<br/>
</div>

## Tech Stack

* **Python:** Version 3.10

* **PyTorch**: Version 2.0.1+cu118

* **Google Colab**: Version FREE


## Details

* This code mainly uses the CNN module from **CNN Explainer (Tiny VGG)** and I followed the **Pytorch in 1 day** course.
* There are 3 main images I would like to share, the loss, accuracy, confusion matrix and some prediction samples. 

<br/>
<br/>
<div align="center">
  <a href="https://i.imgur.com/BprYxHn.png">
    <img src="https://i.imgur.com/BprYxHn.png" alt="Logo" width="810" height="704">
  </a>
<br/>

## I ran the model for 50 epochs on the GPU using Google Colab and it took 1858.9 seconds in total. However, I'm not sure why the test loss went up after going down initially.


<br/>
<br/>

-----------------------------------
<br/>
<br/>

  <a href="https://i.imgur.com/VcwaBa6.png">
    <img src="https://i.imgur.com/VcwaBa6.png" alt="Logo" width="660" height="644">
  </a>
<br/>

## The results of the classification task are satisfactory, but there is one issue that needs to be addressed. The model seems to have difficulty distinguishing between shirts and T-shirts, which are two different categories. To investigate the cause of this confusion, I examined the dataset and realized that the features of the two classes are very similar. Therefore, it might be necessary to either add more distinctive features or merge the two classes into one. Apart from this problem, the model performs well on the other categories.

<br/>
<br/>
-----------------------------------
<br/>
<br/>

  <a href="https://i.imgur.com/e0qtqws.png">
    <img src="https://i.imgur.com/e0qtqws.png" alt="Logo" width="660" height="650">
  </a>
<br/>

## The model makes some errors and cannot distinguish shirts from T-shirts.
<br/>
<br/>

-----------------------------------
<br/>
<br/>

## The Exact Result
 **Epoch: 48** <br>
**Train Loss: 0.0130  | Train Accuracy : 0.9961**
<br>
**Test Loss: 0.4184  | Test Accuracy : 0.9212**
<br>
**==== The Total Time is: 1858.9 Sec  =======**

<br/>
<br/>

-----------------------------------
<br/>
<br/>
</div>


## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Do not forget to give the project a star! Thanks again!

<br/>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.





## References

*  The [source](https://www.learnpytorch.io/?ref=mrdbourke.com)
*  The [CNN Explainer](https://poloclub.github.io/cnn-explainer/)
  
*  


## Contacts
* Via Email: Mahmoud.Nady@Ejust.edu.eg
* Via LinkidIn: https://www.linkedin.com/in/abonady/


