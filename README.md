# Project3
## Project Description
This is a deployable full stack, e-commerce application. Users are allowed to register for an account, search the product listing, add products to their cart and checkout. This readme file supplies the links of the repositories required to deploy and the repository for end-to-end testing. They can be found at:

https://github.com/revature-RCC/project3-backend

https://github.com/revature-RCC/project3-frontend

https://github.com/revature-RCC/project3-e2e


## Technologies Used
* HTML/CSS
* JavaScript
* TypeScript
* Angular 
* Java with Spring Boot
* AWS EC2, S3, and RDS
* Git and GitHub
* Postgres SQL
* Selenium
* JUnit and Mockito
* Cucumber with Gherkin
* Jenkins

## Features
* Users can register an account to checkout products
* Users can log in to their account, uses session checks to prevent subdomain navigation
* Users can search for relative products 
* Users can see products on sale
* Users can add products to their shopping cart
* Users can checkout out their selected products and view the receipt

To-do List;
* Users will be able to view featured products
* Users will be able to reset their password

## Getting Started
To download backend repository:

```git clone https://github.com/revature-RCC/project3-backend.git```

To download frontend repository:
```git clone https://github.com/revature-RCC/project3-frontend.git```

To download selenium e2e testing repository:
```git clone https://github.com/revature-RCC/project3-e2e.git```

To set up enviornment variables:
* update .profile file to include aws credentials, 
```
export AWS_RDS_ENDPOINT='[location of aws ec2 domain]'
export RDS_USERNAME='[ec2 username]'
export RDS_PASSWORD='[ec2 password]'

export P2_S3_ID='[s3 bucket id]'
export P2_S3_Key='[s3 bucker key]'
export P2_S3_REGION='[s3 region]'
export P2_S3_BUCKETNAME='[s3 bucket name]'
export P2_S3_ENDPOINT='[s3 bucket enpoint]'
```


* Download frontend and backend to EC2 server
* User maven to build backend as a package
```mvn package```
* From deploy backend application as a background process
```nohup java -jar [name of build with dependencies].jar & ```
* use web browser to navigate to client side

## Usage
Users will be able to register and login to their e-commerce account

Once logged in, a user will be able to add products into their own cart

Users will be able to search for products and look at sales


## Contributors
Alfred Garcia
Angel DePeña
Jakarai Forsythe
Michael Mikhael

## License
This project uses the license: 
