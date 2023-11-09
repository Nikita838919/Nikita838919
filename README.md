pkg update
pkg upgrade -y
pkg install python -y
pkg install git
git clone
https://github.com/batyaimskiy/DFPhone
cd DFPhone
pip install -r requirements.txt
python dfphone.py
