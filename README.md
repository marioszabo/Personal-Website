# Personal-Website

This project is my attempt to complete [The Cloud Resume Challenge](https://cloudresumechallenge.dev/) in AWS- a multi-step resume project which helps build and demonstrate
skills fundamental to pursuing a carreer in Cloud. The project was published by Forrest Brazeal.  


## How it works



  **Services Used**

 
  - Terraform
  - S3 
  - CloudFront
  - AWS Lambda
  - Github Actions
  - DynamoDB

## [Live Demo 🔗](https://marioszabo.net)


## Summary of the actual code related tasks I had to complete for the challenge:

1. **HTML & CSS**
- Create a resume site written in HTML and styled with CSS

2. **Static S3 Website**
 - Deploy a static S3 website - I used Terraform to deploy the S3 bucket in AWS.

 3. **HTTPS**
  - The website uses HTTPS for security. I used Amazon CloudFront for this.

 4. **DNS**
  - Pointed a custom DNS name to the CloudFront distribution, used Amazon Route 53 for the domain name.

  5. **Javascript**
  - Used Javascript to make a visitor counter to display how many people have accessed the site.

  6. **Database**
   - The visitor counter updates it's count in a db, I used Amazon DynamoDB for this.
   
  7. **API**
   - Used AWS Lambda for the communication between the visitor counter and the database.

  8. **Python**
   - The Lambda function was written in Python's boto3 library.
     
  9. **CI/CD**
   - Created this GitHub repo for the source code of the website, and set up GitHub Actions so when I push new code for the website it automatically
    gets updated in the S3 bucket.

    
   
