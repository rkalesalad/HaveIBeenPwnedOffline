# HaveIBeenPwnedOffline
Search the password list from haveibeenpwned.com locally

## Usage

Take the file `pwned-passwords-sha1-ordered-by-hash-v8.7z` and place it in the samer file as your python file.

Place it in the same folder as `binary_search.py`. 
Currently it should be named 
`pwned-passwords-sha1-ordered-by-hash-v7.txt`. If it has this 
name you do not need to supply a filename for the script to
search in.

After that run the python script. It accepts a list of passwords
as params. On Ubuntu it would look like this:

```shell
python binary_search.py "paSsword" "anotherSecurePassw0rd"
```

If the password contains characters which could be encoded 
differently with different encodings 
