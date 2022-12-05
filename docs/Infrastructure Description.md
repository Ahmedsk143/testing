# Infrasctructure Description

### RDS Postgres

- The application server uses AWS RDS Postgres as database for storing and retrieving information.
  - Endpoint: http://udagramapi-env.eba-dfmjmpbp.us-east-1.elasticbeanstalk.com/
  - Port: 5432

### Elastic Beanstack

- It is used for the backend code.
  - Endpoint: http://Udagramapi-env.eba-dfmjmpbp.us-east-1.elasticbeanstalk.com

### S3 Bucket

- The frontend application is deployed using AWS S3 Bucket. The bundled assets are uploaded to an S3 bucket and that bucket is made publicly readable. This is used for the end users
  - Endpoint: http://frontendhostudagram.s3-website-us-east-1.amazonaws.com
