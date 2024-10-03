# AWS Goodies: CLI and Python scripts

## setup AWS CLI
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## create python venv
```
$ python -m venv .venv
$ chmod +x .venv/bin/activate
```

## set python venv
```
## if you do not use direnv:
$ source .venv/bin/activate

## if you use direnv:
$ direnv allow
```

### `$ which python` should return 
> .venv/bin/python

## install required python packages into venv
`$ pip install -r requirements.txt`

## run scripts 
Scripts have the proper interpreter set in the shebang, so just execute them from your shell:  
`$ fmsquery`
