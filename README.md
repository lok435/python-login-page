# python-login-page

## pre-requirement 
Python >3.8


## DB creation and table setup

```
create database anand;
```

```
CREATE TABLE accounts (
    id int NOT NULL AUTO_INCREMENT,
    username varchar(255) NOT NULL,
    email varchar(255),
    password varchar(255) NOT NULL,
    PRIMARY KEY (id)
);
```

## How to run the Application

1. git clone <repo>
2. cd <repo>
3. python3 -m venv venv
4. source venv/bin/activate
5. pip install -r requirements.txt
6. chmod 777 run
7. nohup ./run &
