# python flask tutorial

#### setup projecy

- clone repository and enter its folder

- use python3 as env

    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

- install requirements

    `pip install -r requirements.txt`

- copy development configurations

    ```
    mkdir -p instance
    cp flaskr/config_dev.py instance/config.py
    ```


#### launch app

```
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```
