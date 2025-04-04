# decoder
usage: 

In Windows :
python decoder.py --b64/--b32 cipher

In Linux :
./decoder.py --b64/--b32 cipher

Python script to decode base64 and base32 encodings

options:

  -h, --help              show this help message and exit
  
  --b64  [base64 ...]     decode base64 encoding
                        
  --b32  [base32 ...]     decode base32 encoding
                        
  -v                      print version

Windows
-------
Example: decoder.py --b64 aGVsbG8=

Linux
-----
chmod +x decoder.py

Example : ./decoder.py --b64 aGVsbG8=
