# laravel-playground

## 環境構築(Homestead) on Windows 10 with Cygwin
1. Install `Virtual box` and `Vagrant` your PC.
2. run `mkdir homestead` and `cd homestead`
3. run `vagrant box add laravel/homestead`
4. run `git clone https://github.com/laravel/homestead.git Homestead`
5. setting homestead -> [ja doc](https://readouble.com/laravel/5.1/ja/homestead.html#Homestead設定)
6. run `vagrant up`
7. complete. Enter the virtual environment with `vagrant ssh`.

If you change the `sites` property after provisioning the Homestead box, you should re-run `vagrant reload --provision` to update the Nginx configuration on the virtual machine.
