name="winetricks"
package_name="winetricks"
description="winetricksWindowsエミュレーターソフトウェア"
run_preparing=false
install(){
rm -rf /tmp/winetricksinstall
mkdir /tmp/winetricksinstall
cd /tmp/winetricksinstall
wget https://raw.githubusercontent.com/Winetricks/winetricks/master/src/winetricks
sudo mv winetricks /usr/bin/
sudo chown root:root /usr/bin/winetricks
sudo chmod 755 /usr/bin/winetricks
rm -rf /tmp/winetricksinstall
}
uninstall(){
sudo rm -f /usr/bin/winetricks
}