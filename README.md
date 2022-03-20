



  
  
[//]: # (____________________________________PROJECT TITLE____________________________________)

<br>

<h1 align="center">
  <img src=https://github.com/najwasaeed44/data-science-project-theme/blob/main/img/logo.png?raw=true" width="100px"/><br/><br>
PROJECT TITLE
</h1>
                                                                                                                    <hr style="height:1.5px;border-width:10;color:blue;background-color:black">


<br><br><br><br>


[//]: # (____________________________________BACKGROUND____________________________________)

<img src="https://images.genial.ly/59e059d30b9c21060cb4c2ec/5bbf17763292ef649e9b810f/175cbb1e-df65-405a-9cd0-cf177e1a2f00.gif?genial&1633910400074" width="60" height="70" align="left">

## Background:
<hr style="height:1.5px;border-width:10;color:blue;background-color:black">


Our company develops innovative Artificial Intelligence and Computer Vision solutions that revolutionize industries. Machines that can see: We pack our solutions in small yet intelligent devices that can be easily integrated to your existing data flow. Computer vision for everyone: Our devices can recognize faces, estimate age and gender, classify clothing types and colors, identify everyday objects and detect motion. Technical consultancy: We help you identify use cases of artificial intelligence and computer vision in your industry. Artificial intelligence is the technology of today, not the future.


<br><br>

[//]: # (____________________________________DATA DESCRIPTION____________________________________)


<img src="https://media.baamboozle.com/uploads/images/67969/1595412283_471863"  width="60" height="70" align="left">

## Data Description:
<hr style="height:1.5px;border-width:10;color:blue;background-color:black">

We collected page flipping video from smart phones and labelled them as flipping and not flipping.

We clipped the videos as short videos and labelled them as flipping or not flipping. The extracted frames are then saved to disk in a sequential order with the following naming structure: VideoID_FrameNumber.

<br><br>


[//]: # (____________________________________ATTRIBUTES____________________________________)

<img src="https://c.tenor.com/1_5w5vXEH5gAAAAj/mandalorian-star-wars.gif" width="60" height="60" align="left">

## Goal(s)::
<hr style="height:1.5px;border-width:10;color:blue;background-color:black">

Predict if the page is being flipped using a single image.

<br><br>


[//]: # (____________________________________PROJECT OVERVIEW____________________________________)


<img src="https://media0.giphy.com/media/LmqdA28jZ7bitDeDWr/200.webp"  width="60" height="60" align="left">

## Project Overview:
<hr style="height:1.5px;border-width:10;color:blue;background-color:black">

### data preprocessing:

The original data set size was `1080 * 1920` pixels with two classes, `flip` and `notflip` class as in the following picture.


<br><br>


[//]: # (&#40;____________________________________ CONCLUSION____________________________________&#41;)

<img src="https://media4.giphy.com/media/MbMUCH4MUffka1ZFeT/giphy.gif?cid=790b7611040baf4e7332c491694685e3367d8fe931cd7a69&rid=giphy.gif&ct=s"  width="80" height="60" align="left">

## Conclusion:
<hr style="height:1.5px;border-width:10;color:blue;background-color:black">

Different model hyperparameters were tested and in general, some of the models prefer well in the range of **10** epochs. From the training and optimization section, it's clear this data prefer a learning rate of around 0.001 and tanh activation function better than relu. Our best model test score is `99.7%` with a loss equal to `0.046`.


                                                                          
  <br><br>                                                                        
  
| Option | Description                                              | Type   | Default | Required? |
| ------ | -------------------------------------------------------- | ------ | ------- | --------- |
| `-t`   | Enables to define custom backend and frontend templates. | `bool` | `false` | No        |



> If you're looking for the **Create Go App CLI** for Go `1.16`, you can find it [here](https://github.com/create-go-app/cli/tree/v2).
Installation is done by using the [`go install`](https://golang.org/cmd/go/#hdr-Compile_and_install_packages_and_dependencies) command and rename installed binary in `$GOPATH/bin`:

```bash
go install github.com/create-go-app/cli/v3/cmd/cgapp@latest
```


```bash
# Tap a new formula:
brew tap create-go-app/cli
# Installation:
brew install create-go-app/cli/cgapp
```

