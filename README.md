A Gym Member Manager Web App using Django and AWS Services

Manages and keeps track of all payments and members


- Install all dependencies by executing the following command:

    ```
    $pip install -r requirements.txt
    ```

- For running the application simply execute the following commands:

    ```
    $python3 manage.py migrate
    $python3 manage.py runserver
    ```

- For creating a user execute:

    ```
    $python3 manage.py createsuperuser
    ```

- You can now login to the system!


- AWS Elastic Beanstalk setup:

    ```
    $pip install awsebcli
    $eb init
    $eb create
    $eb status
    $eb deploy
    $eb open
    ```
