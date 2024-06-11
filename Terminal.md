run Mineserver.ipynb
#
curl -s "https://get.sdkman.io" | bash
sdk install java 8.0.412-zulu -y
sdk default java 8.0.412-zulu
#
chmod +x ./startturnel.sh
./startturnel.sh
#
chmod +x ./online.sh
./online.sh
#
chmod +x ./LaunchServer.sh
./LaunchServer.sh
