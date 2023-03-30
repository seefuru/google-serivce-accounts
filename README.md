# Create_Google_Services_Accounts

## Create Services Account With Termux. 

# You need 

Python3, git installed first

# termux-setup-storage

# cd /sdcard

# git clone https://github.com/AtrociousMirrorBot/Create_Google_Services_Accounts

# cd Create_Google_Services_Accounts

# pip3 install -r requirements.txt

# For Download token.pickle
 
python3 generate_drive_token.py

## Copy url and paste in browser and give permission. In Create_Google_Services_Accounts folder a token.pickle will create.


For Make Services Accounts 

# python3 gen_sa_accounts.py --list-projects

# python3 gen_sa_accounts.py --enable-services $PROJECTID


# python3 gen_sa_accounts.py --create-sas $PROJECTID

# python3 gen_sa_accounts.py --download-keys $PROJECTID

# cd accounts

# grep -oPh '"client_email": "\K[^"]+' *.json > emails.txt
