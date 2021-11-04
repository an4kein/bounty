# bounty

create screenshot with redirect

`for i in $(cat httpx-sites.txt); do google-chrome $i --password-store=basic &; sleep 5s; flameshot screen -p ~/client/test/screenshot-HTTPS ;sleep 5;pkill -9 chrome; done`
