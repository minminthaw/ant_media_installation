<h1 align=center>This tutorial is tested on ubuntu 20.04 LTS(By Tech Online Class)</h1>

# 1.Download Ant Media Server source code
Ant Media Server Source code ကို https://github.com/ant-media/Ant-Media-Server/releases အဲ့လင့်ကနေ အဆင်ပြေရာ Version ကို Download ဆွဲပြီး မိမိ Ant Media Server တင်မယ့် vps ပေါ်က root folder ထဲမှာ upload တင်လိုက်ပါ။

# 2.Install Ant Media Server
wget https://raw.githubusercontent.com/ant-media/Scripts/master/install_ant-media-server.sh</br>
chmod 755 install_ant-media-server.sh

sudo ./install_ant-media-server.sh ant-media-server.zip</br>
ပြီးတဲ့အထိ စောင့်လိုက်ပါ။

ပြီးသွားတဲ့အခါ Login ဝင်ရမယ့် Link က</br>
http://yourip.com:5080 ဖြစ်ပါမယ်</br>

<h2>SSL Install ပြုလုပ်နည်း</h2>(မလုပ်လည်းရ)
cd /usr/local/antmedia</br>
sudo ./enable_ssl.sh -d yourdomain.com</br></br>

ssl install ပြုလိုက်လိုက်လျှင်တော့ သင့်ရဲ့ Login link က
http://yourip.com:5443 ဖြစ်သွားပါမယ်။
