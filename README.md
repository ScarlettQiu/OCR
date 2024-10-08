# OCR
Optical Character Recognition
This project mainly aims to explore how to build OCR in Python.  

# Pre-requisite  
## Homebrew for Mac  

### What is Homebrew?   
Here is link to understand homebrew: https://brew.sh/ 

### Why do we need Homebrew?  
To install the popular package Tesseract, we need Homebrew on Mac.  

About Tesseract: https://github.com/tesseract-ocr/tesseract

### Install Homebrew
#### 1. Paste below command in macOS Terminal  
<code> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" </code>

![image](https://user-images.githubusercontent.com/93269907/232903664-eb341c8c-68fb-4289-a5df-6e540d939d39.png)

#### 2. Run below command in the Terminal  
<code> eval "$(/opt/homebrew/bin/brew shellenv)" </code>

![image](https://user-images.githubusercontent.com/93269907/232903939-ca466b60-a4d2-459b-b327-0b42845364f5.png)

Once we have the homebrew installed, we could start to install Terresact.  

# Install Terresact  
#### 1. Run below the command
<code> brew install tesseract </code>  
It may take several minutes to complete the installation.   
![image](https://user-images.githubusercontent.com/93269907/232904805-e74328b7-c444-43d5-bf8d-a7a5d719bdae.png)

### 2. Check the path of Tesseract
<code> which tesseract </code>  
<code> brew list tesseract </code>
