# My_first_ubuntu_ultrabook

Settings of my ubuntu ultarboook

1.Get the su passwd

  sudo passwd root
  
2.Install google chrome

  sudo wget http://www.linuxidc.com/files/repo/google-chrome.list -P /etc/apt/sources.list.d/
  wget -q -O - https://dl.google.com/linux/linux_signing_key.pub  | sudo apt-key add -
  sudo apt-get update
  sudo apt-get install google-chrome-stable
  
3.Install shadowsocks-qt5

  sudo add-apt-repository ppa:hzwhuang/ss-qt5
  sudo apt-get update
  sudo apt-get install shadowsocks-qt5

  PAC file:/My_first_ubuntu_ultrabook/Shadowsocks
  
  In system settings:file:///the_path_of_the_pac_file/autoproxy.pac
  
4.Install
