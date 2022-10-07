# derive-nornir

Start Python virtual environment
```
git clone https://github.com/Radmanded/derive-nornir.git
cd derive-nornir
python -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
pip install -r requirements.txt
python runbook1.py
```

Troubleshoot device ssh connectivity
```
cd ~/.ssh  - delete ssh history

$ sudo nano etc/ssh/ssh_config

(uncomment) StrictHostKeyChecking (ask) no
(uncomment) Ciphers aes128-ctr


(add to end of list)    PubkeyAcceptedAlgorithms +ssh-rsa
                        HostkeyAlgorithms +ssh-rsa

```
