# How to use the tool?

### 1. Install the required dependencies.

```shell
pip install -r requirements.txt
# or
python3 -m pip install -r requirements.txt
```

### 2. Edit the **demats.txt** file and add all the accounts' information each account separated by a line break and each information separated by comma ',' and no spaces.

<br>

```
FORMAT of demats.txt file
    Name,DP-ID,USERNAME,PASSWORD,CRN,TXN-PIN


Example
    Harry Hamal,11400,00121321,Dollar@123,0000458454,1254


Note: Name provided in the demats.txt file is just for showing the progress in
      log and does not need to be the name used in the meroshare account.
```

### 3. After adding the account info's, execute the following command from the parent directory.

```
python ./main.py
# or
python3 ./main.py
```