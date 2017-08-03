wget --save-cookies cookies.txt --keep-session-cookies --no-check-certificate 'https://drive.google.com/uc?export=download&id=FILEID' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/Code: \1\n/p'
 
wget --load-cookies cookies.txt 'https://drive.google.com/uc?export=download&confirm=CODE_FROM_ABOVE&id=FILEID'
