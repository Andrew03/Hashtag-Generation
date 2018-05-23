# Hashtag-Generation

This is a [PyTorch](https://pytorch.org/ "PyTorch") implementation of a hashtag generator. The generator takes in an input image and tries to generate associated hashtags. The generator is based off a sequence to sequence model and is trained on the [HARRISON](https://github.com/minstone/HARRISON-Dataset "HARRISON") datset.

## Prerequisites
* PyTorch 0.4

## Installation
1. Clone the repository
`git clone https://github.com/Andrew03/Hashtag-Generation`

## Setup Data
1. Download and extract the [HARRISON](https://github.com/minstone/HARRISON-Dataset "HARRISON").
`git clone https://github.com/minstone/HARRISON-Dataset`
2. Torrent the images.
Download a torrent service such as [Deluge](https://deluge-torrent.org/ "Deluge"). 
Then torrent the `HARRISON-Dataset/HARRISON/HARRISON_dataset.torrent` file.
3. Extract the images.
Untar the result of the torrent, `HARRISON_full.tar`.
`tar xzf HARRISON_full.tar`
4. Create a soft link to the data 
`mkdir data`
`ln -s $HARRISON data/HARRISON`
