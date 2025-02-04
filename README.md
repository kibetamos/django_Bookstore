# Bookstore Project - Python

This is a bookstore python-django project that uses Docker, includes a custom user model, and implements tests.

## Bookstore Project Structure

- `Dockerfile`: Defines the Docker image for the application.
  
- `docker-compose.yml`: Defines the services and dependencies for the Docker containers.
  
- `config/`: Directory to store the application code.
  
- `tests/`: Directory to store the test code.
  
- - `gitignore/`: Store code to be ignored.
 
## CI/CD and DevOps

This project incorporates a CI/CD pipeline using GitHub Actions to automate the testing, building, and deployment processes. Key features include:

  1. Automated Testing: Each code change triggers automated tests to ensure the application’s functionality remains intact.
    
  2. Continuous Deployment: Successful builds are automatically deployed to staging or production environments, facilitating quicker releases.
The application is containerized using Docker, ensuring consistency across different environments. This minimizes the "it works on my machine" issues.

The docker-compose.yml file allows you to define and run multi-container Docker applications, simplifying the management of application dependencies and configurations.

## Setup

1. Clone the repository:

      - git clone https://github.com/kibetamos/django_Bookstore.git

3. Enable the virtual environment;
   
      - source env/bin/activate

4. Install requirements file  by running:
      - pip install -r requirements.txt
  
5. Start the project:

      - python manage.py runserver
  
      - Access it on port 8000 localy
   
   

    
