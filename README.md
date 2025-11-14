# Deploy-a-static-website-on-S3-with-CloudFront-CDN


## A full, step-by-step tutorial with screenshots showing how to put a static website in an S3 bucket and serve it worldwide using CloudFront.


### This project demonstrates how to put a static website in an S3 bucket and serve it worldwide using CloudFront. Including how to:

* Create an S3 Bucket and Upload Content to that S3 Bucket


#### Step-by-Step instructions with screenshots on how to put a static website in an S3 bucket and serve it worldwide using CloudFront.



**Create an S3 Bucket**

*Before setting up the S3 bucket, download a template ZIP file (e.g., from HTML5 UP or GitHub Pages), extract it, and save the folder containing `index.html` and the `css` directory in an easily accessible location.




* Select by typing S3 from the AWS Searchbar

<p align="center">  
  <img src="resources/S3 Search for S3 in AWS Searchbar.png" alt="Select S3 from AWS Search Bar" />  
</p>  

* Select Create Bucket

<p align="center">  
  <img src="resources/S3 Select Create Bucket ALL.png" alt="Create an S3 Bucket" />  
</p>  

* Give Your Bucket a Name in the Bucket Name Box.

<p align="center">  
  <img src="resources/S3 Create a Bucket Name.png" alt="Give S3 Bucket a Name" />  
</p>  

* Select Create Bucket at the Bottom.
<p align="center">  
  <img src="resources/S3 Select Create Bucket ALL.png" alt=" Select Create Bucket at Bottom" />  
</p>  

**Upload the content to the S3 Bucket**

* Select the Recently Created Bucket
<p align="center">  
  <img src="resources/S3 Select the recently created Bucket.png" alt="Select the Recently Created Bucket" />  
</p>  

* Select the Upload Button.
<p align="center">  
  <img src="resources/S3 Select the Upload Button ALL.png" alt="Select the Upload Button" />  
</p>  

* Select both the earlier-created css folder and index file.  

<p align="center">  
  <img src="resources/S3 Select File & Folder for Drag and Drop.png" alt="Select File & Folder for drag and drop" />  
</p>  


*Drag and drop both files into the Files and Folders section.

<p align="center">  
  <img src="resources/S3 post drag and drop file and folder to s3 bucket.png" alt="File and Folder in S3" />  
</p>  


* Select Upload from the bottom of the page


<p align="center">  
  <img src="resources/S3 Select the Upload Button ALL.png" alt="Select Upload Button at Bottom." />  
</p> 


**Create a Distribution in CloudFront that uses Amazon S3 origin with Origin Access Control.**


* Select by typing CloudFront from the AWS Searchbar

<p align="center">  
  <img src="resources/CLOUDFRONT search cloudfront AWS Searchbar.png" alt="Select CloudFront AWS Searchbar." />  
</p> 


* Select Create a CloudFront Distribution.

<p align="center">  
  <img src="resources/CLOUDFRONT Select Create Cloudfront Distribution.png" alt="Select Create CloudFront Distribution." />  
</p> 

* Give a Name for your CloudFront Distribution in the Distribution Name box.

<p align="center">  
  <img src="resources/CLOUDFRONT Give name for CloudFront.png" alt=" Give CloudFront Distribution Name." />  
</p> 

* Click Next at the bottom of the page.

<p align="center">  
  <img src="resources/CLOUDFRONT Select Next ALL.png" alt=" Click Next Bottom Page." />  
</p> 
* Select Amazon S3 as the Origin Type

<p align="center">  
  <img src="resources/CLOUDFRONT Select Amazon S3 Origin Type.png" alt="Select Amazon S3 Origin Type." />  
</p> 

* Select the Browse S3 Button and choose the S3 Bucket that was created earlier.

<p align="center">  
  <img src="resources/CLOUDFRONT Select S3 origin.png" alt="Select S3 Origin." />  
</p> 

* Select the Settings as they are illustrated below.

 <img src="resources/CLOUDFRONT Settings Setup.png" alt="Select Settings." />  
</p> 



* Click Next at the bottom of the page.

<p align="center">  
  <img src="resources/CLOUDFRONT Select Next ALL.png" alt="Click Next Bottom Page." />  
</p> 

* Select Enable Security Protections from the Enable Security Box.

<p align="center">  
  <img src="resources/CLOUDFRONT Enable WAF.png" alt="Select Enable Security." />  
</p> 

* Click Next at the bottom of the page.


<p align="center">  
  <img src="resources/CLOUDFRONT Select Next ALL.png" alt="Click Next Bottom of Page." />  
</p> 

* Select Create Distribution at the bottom of the following page.


<p align="center">  
  <img src="resources/CLOUDFRONT Select Create Distribution end of cloudfront setup.png" alt="Select Create Distribution Bottom Page." />  
</p> 



























