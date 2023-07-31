Barrier (share mouse/keyboard)
==============================

`openssl x509 -fingerprint -sha256 -noout -in ~/.local/share/barrier/SSL/Barrier.pem | sed -e "s/.*=/v2:sha256:/" > ~/.local/share/barrier/SSL/Fingerprints/Local.txt`

`openssl req -x509 -nodes -days 365 -subj /CN=Barrier -newkey rsa:4096 -keyout Barrier.pem -out Barrier.pem`
