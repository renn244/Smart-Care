### Prerequisites
1. Make sure you have the following installed:
    - [python](https://www.python.org/) (python 3 recommended)
    - [pip] (https://packaging.python.org/en/latest/tutorials/installing-packages/)

2. Clone the repository:
    ```bash
        git clone https://github.com/DaniellDavid123/Smart_Care.git
    ```

3. Create a Venv:
    ```bash
        python -m venv venv
    ```

4. Activate venv and install packages:
    **Window**
    ```bash
        ./venv/Scripts/activate
        pip install -r requirements.txt
    ```
    **Linux**
    ```bash
        source venv_name/bin/activate
        pip install -r requirements.txt
    ```

5. Start:
    ```bash
        cd SmartCare
        python manage.py runserver
    ```