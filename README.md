# Get-Started-with-Azure-student
How to create an azure student account and create your very first prototype!

## Creating an Azure student account 

## Using GPT4 turbo vision to describe images and generate a prompt 

1) Login to portal.azure.com
2) If everything is right, you have a visual studio professional subscription
3) Go to Resource groups in your settings
4) Create a Resource called chatbotters and fill in the info in the image below <br></br>
    <a href="https://ibb.co/3hsdzRT"><img src="https://i.ibb.co/4Nftd1F/Screenshot-2024-11-29-at-09-45-42.png" alt="Screenshot-2024-11-29-at-09-45-42" border="0"></a>
5) Click on develop. You will see Keys and endpoint. You will need this later on to get permission to use this resource group <br></br><br></br>
<a href="https://ibb.co/PCWjtSk"><img src="https://i.ibb.co/YjdQbrg/Screenshot-2024-11-29-at-09-51-45.png" alt="Screenshot-2024-11-29-at-09-51-45" border="0"></a>
6) Click on Model deployments, you will be redirected to https://oai.azure.com <br></br>
<a href="https://ibb.co/bznVyRc"><img src="https://i.ibb.co/3BHb8Yg/Screenshot-2024-11-29-at-10-07-40.png" alt="Screenshot-2024-11-29-at-10-07-40" border="0"></a>
7) Click on + deploy model 
8) Choose GPT 4
9) Choose by deployment type standard
10) Choose vision preview
11) Rate minimum on max 
12) Choose a good deployment name, you will need it later. I chose GPT4Vision
13) Click on deploy <br></br>
<a href="https://ibb.co/ctyf4c9"><img src="https://i.ibb.co/HYKw5Dy/Screenshot-2024-11-29-at-10-18-27.png" alt="Screenshot-2024-11-29-at-10-18-27" border ="0"></a>
14) Open in playground
15) Go back to Portal.azure.com
16) Go to manage deployments, Now you can check that there is a deployment model made for this resource group
17) If you have a macbook, install Homebrew
18) Install Micromamba with Homebrow or without in your terminal (https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html)
19) Create an environment With micromamba in visual studio code (If you don't have visio studo code install this) (https://prefix.dev/docs/mamba/environments) micromamba create -n multimodal-azure-env -c conda-forge python=3.12 jupyter  
 
micromamba activate multimodal-azure-env <br></br>
<a href="https://ibb.co/nbzcqmT"><img src="https://i.ibb.co/FKgwk39/Screenshot-2024-11-29-at-10-32-28.png" alt="Screenshot-2024-11-29-at-10-32-28" border="0"></a>
20) Create a jupiter Notebook file 
21) Click on command shift P and select your environment in visual studio code
22) Select your environment again next to outline and the three dots in visual studio code
23) Type the following in your terminal in visual studio code: pip install openai
24) Use the code given in this project, and you are done!


  


