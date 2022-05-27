# MAAD-Final-Project

This is my final project for MAAD 26210: Media Art and Design Practice.

## Overview

The general idea is to create AI-generated poems from a set of images. I accomplish this with two separate components.

The first is a [notebook](MediaArtDesignPracticesFinalImageCaptioning.ipynb) that can caption images using CLIP embeddings and GPT2. The way this works is the image is encoded using CLIP and then that encoding is used to fine-tune the existing GPT2 language model which will produce a caption for the image.

The second component is an interactive webpage that allows users to customize their own AI-generated poems from a subset of images. This demo takes five images obtained from a google image search for the word summer. It allows users to mix and match these images resulting in a poem consisting of the selected images' captions.


## How to use the interactive webpage to create a poem

First, click on the images that you want to contribute to the poem. Next, click the "Create Poem" button to display the AI-generated poem based on the selected images.