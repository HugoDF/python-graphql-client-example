# Python GraphQL client example

An example consuming a GraphQL API from Python using gql. 

## Run using virtualenv

```sh
$ virtualenv venv -p python3
```

```sh
$ source ./venv/bin/activate
```

```sh
$ pip install -r requirements.txt
```

```sh
$ python fetch.py
{'pokemon': {'attacks': {'special': [{'name': 'Discharge'}, {'name': 'Thunder'}, {'name': 'Thunderbolt'}]}}}
```