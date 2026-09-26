TURMUX COMMAND 
......... 

pkg update && pkg upgrade -y
pkg install git python -y 
git clone https://github.com/samimaktar-hw/SMS-Automation-.git
cd SMS-Automation-
pip install -r requirements.txt
chmod +x HexcaWeb.sh
./HexcaWeb.sh
python bomber.py
