# as.tabchi
آموزش نصب با ارسال یک دستور: git clone https://github.com/AmWrHoSein/tabchi.git &amp;&amp; cd tabchi &amp;&amp; chmod 777 diamond.sh &amp;&amp; chmod 777 install.sh &amp;&amp; ./install.sh ----------------------------- بعد از اتمام مراحل نصب برای ساخت اولین ربات تبچی دستور زیر را وارد کنید: lua creator.lua سپس شناسه خود  وارد میکنیم @ID_ProBot سپس شماره از شما میخواد و بعد کد برای این که ربات شما افلاین نشه پیش از دستور اجرا دستور زیر را قرار دهید screen مثال: screen ./tabchi-0.sh ______________________________ پیش نیاز های ضروری  wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz  tar zxpf luarocks-2.2.2.tar.gz  cd luarocks-2.2.2  ./configure; sudo make bootstrap  sudo luarocks install luasocket  sudo luarocks install luasec  sudo luarocks install redis-lua  sudo luarocks install lua-term  sudo luarocks install serpent  sudo luarocks install dkjson  sudo luarocks install lanes  sudo luarocks install Lua-cURL sudo luarocks install luaxmlrpc _________________________ کد های زیر هم پیش نیازه حتما نصب کنید اکثرا ارور میده: sudo apt-get install libstdc++6 sudo add-apt-repository ppa:ubuntu-toolchain-r/test  sudo apt-get update sudo apt-get upgrade sudo apt-get dist-upgrade ________________________   موفق باشيد
