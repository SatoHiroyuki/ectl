

## Usage

```
usage: ectl [-h] [-a AWS_ACCESS_KEY_ID] [-s AWS_SECRET_ACCESS_KEY]
            [--profile PROFILE] -r REGION [-n TAGNAME] [-f FILENAME]
            {start,stop}

Instance Start Stop

positional arguments:
  {start,stop}          you can select function in ['start', 'stop'].

optional arguments:
  -h, --help            show this help message and exit
  -a AWS_ACCESS_KEY_ID, --aws-access-key-id AWS_ACCESS_KEY_ID
                        AWS Access Key
  -s AWS_SECRET_ACCESS_KEY, --aws-secret-access-key AWS_SECRET_ACCESS_KEY
                        AWS Secret Access Key
  --profile PROFILE     Profile name of AWS shared credential file entry.
  -r REGION, --region REGION
                        AWS Region
  -n TAGNAME, --name TAGNAME
                        Name_Tag
  -f FILENAME, --filename FILENAME
                        List File
```

