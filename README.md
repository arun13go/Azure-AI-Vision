# Azure-AI-Vision

## Overview
Sample python code and API to index the vidoe files and extract the insights and store in the blob storage


## Official Applied AI services| Video Indexer API page
This folder contains the basic ways to address Video Indexer's API in order to allow full engagment with the product: Get Account, Get Access token through ARM API, upload a video, polling on status/waiting, and indexing the video. It is highly recommend to first read the more detailed documentation which can be found here.

For more API abilities, please visit our API documentation

## Contents
The sample code demonstrates important aspect of uploading and indexing a video for ARM-based accounts, availble from December 2021. Following the code will give you a good idea of how to use our API for basic functionalities. Make sure to read the inline comments and notice our best practices advices.

## Prerequisites
Instructions:

The main program to run the API samples is provided as a Jupyter notebook - video_indexer_api_samples.ipynb

Go to video_indexer_api_samples.ipynb and populate SubscriptionId with your subscription id

Go to video_indexer_api_samples.ipynb and populate ResourceGroup with your resource group

Go to video_indexer_api_samples.ipynb and populate AccountName with your account name

Go to video_indexer_api_samples.ipynb and populate VideoUrl with your video url

Go to video_indexer_api_samples.ipynb and populate ExcludedAI with the AI's you want to exclude from the indexing job.

Go to video_indexer_api_samples.ipynb and populate VideoUrl and LocalVideoPath with publicly accessed video Url and/or with local path to video file.

Review the VideoIndexerClient/VideoIndexerClient.py file to learn about the implementation of the API. The Client can be replaced easily with your custom behavior. Note the section of issuing Video Indexer Access Token. (The Token is Valid for 30 minutes).

Make sure all requirements are installed. The list of requirements is provided in the file requirements.txt

Run the cells in the Jupyter notebook - video_indexer_api_samples.ipynb

For more information visit here
