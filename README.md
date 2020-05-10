# Download & Install Cloud-IP Windows & Termux Working

# Cara Eksekusi di Windows :

Download Python : https://www.python.org/downloads

choco install unrar

choco install wget


# Download Cloud-IP Via GoogleDrive

wget -O Cloud-IP.rar https://drive.google.com/uc?id=1QhdSCLmWvx4hdgfqm_4FRdgbnOoBSbP-&export=download

unrar x Cloud-IP.rar

rm Cloud-IP.rar

cd Cloud-IP

chmod 777 cloudip.py

pip install -r requirements.txt

python cloudip.py -h

==============================================================================
# Cara Eksekusi di Termux :

pkg update & upgrade

pkg install git tor -y

# Download Cloud-IP Via Github

git clone https://github.com/ProjectorBUg/Cloud-IP.git

cd Cloud-IP

chmod +x CloudIP.sh

./CloudIP.sh

# Tunngu Download CloudIP Selesai Okeh...

cd CloudIP 

chmod +x cloudip.py

pip3 install -r requirements.txt

python3 cloudip.py -h

# Run tor

tor

# NB : Khusus Termux klau gk bisa pip3 install -r requirements.txt,,bisa pakai pip install -r requirements.txt
