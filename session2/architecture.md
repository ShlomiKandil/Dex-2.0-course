# Session 2 homework
Architecture of a validation users website for banks.

## Model - ms
    I would use the Decompose by business capability to define services. This is how we get 
    a loosely coupled services which is very important.
    microservices:
        - IAM service
        - ID Validation
        - Userdetails
            - income,worklist
        - Searchbox       
## Model - db
    I would use Database per Service model so each service has its own private database.
    It helps us to keep the loosely coupled priciple. Changes one servoce wont effect the other.
    It also gives is the ability to suite DB to the service needs.
    
## Model - observability
    Will use splunk for data analyzing and dashboards.
    
## Model - integration
    - S3 for storage
    - kafka for events and crtical issues like payments.

