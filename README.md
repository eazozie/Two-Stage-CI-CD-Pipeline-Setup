# A Two-Stage CI/CD Pipeline Setup 


## Project Details:

I will be setting up a two-stage CI/CD pipeline using CodePipeline to automatically deploy a static website on an Amazon S3 bucket.
The website will be a simple HTML webpage displaying my name, **”EBUBECHUKWU AZOZIE”**.
I will be sourcing my code from my personal GitHub account.

## Stage 1 - Source from GitHub 
## Stage 2 - Deployment to S3 bucket 


## Step 1

Setting up my S3 bucket and enabling static website hosting, also using S3 bucket policy to enable internet access

<img width="975" height="496" alt="image" src="https://github.com/user-attachments/assets/f05bc53a-190a-47e2-ab65-ebd26f6cb029" />



Setting index document as index.html
S3 Bucket host link http://eazozie.com.s3-website-us-east-1.amazonaws.com

The json format bucket policy used


<img width="975" height="433" alt="image" src="https://github.com/user-attachments/assets/e590afc7-69d2-4bce-81a5-a0341cbc6b80" />


## Step 2

Creating a GitHub repository and cloning it to my local repository, then push my HTML code to the GitHub repository 



<img width="975" height="294" alt="image" src="https://github.com/user-attachments/assets/2e8bcf06-8edc-42b0-ae7c-db1a5e9f8646" />


## Step 3

Creating a CI/CD pipeline using AWS CodePipeline

<img width="975" height="654" alt="image" src="https://github.com/user-attachments/assets/b21fdb93-fe5d-4ed3-81e7-12d022a5e6f3" />

Pipeline successfully created  



## Step 4

Testing with my S3 bucket link http://eazozie.com.s3-website-us-east-1.amazonaws.com


<img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/42929fac-7eb5-4f72-97bc-ec5c76327d3f" />




