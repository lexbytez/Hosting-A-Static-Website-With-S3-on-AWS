# Hosting-A-Static-Website-With-S3-on-AWS
A new startup business in North America has recruited you to help with the launch of a quick-access, low-cost static website. You've decided to complete this contract by hosting and deploying their website utilizing AWS S3
Steps to follow

Open your Amazon Aws Console and head to S3

Open a bucket under S3
When setting up allow public access to the bucket
![1](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/858189a9-1a18-4eff-9501-779c431aa444)
![2](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/2db7cd83-90ba-4faa-869e-c5230f0d4435)
![3](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/c420f1c4-68b6-4e0a-afbc-0a9df8fd1ed4)
Next step

Upload given website source Code to bucket

when done go to properties under created bucket and enable static hosting, save the changes
![4](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/b1ecc2e8-1dbb-438d-a052-d1f904675879)
![5](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/fbe83b42-4122-41f0-a86c-1e87118cd6cd)
When this is done and saved your public access link will automatically be generated -->>

http://techchakroadmapslexbyte.s3-website-us-east-1.amazonaws.com

but will bring up 403 error when trying to access it
![1](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/5b24f755-b2a3-47dd-b1ab-376bf0f42724)
Head to objects click all the files in folder and choose action Make public using ACL
![1](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/8d0cbb9b-381c-49bd-94a9-f4d298b30d61)
![2](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/3fb6da3b-1223-4524-a581-c1662cdd5bd7)
When done website page would be fully running
![3](https://github.com/lexbytez/Hosting-A-Static-Website-With-S3-on-AWS/assets/128375535/d0d6b6c4-bd43-4058-bc50-71dd269e68e0)


