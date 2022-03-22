gpg -c source.tar.gz
gpg -d --passphrase 123456789 source.tar.gz.gpg | tar -xzvf -
gpg --batch --passphrase-file pass.txt --output source.tar.gz source.tar.gz.gpg