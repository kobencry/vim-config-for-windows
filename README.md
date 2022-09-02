## vim-config-for-windows


#### Langkah awal untuk melakukan vim plug

#### 1. buka terminal windows powershell, lalu copy sumber kode dibawah ini:
###### Windows (PowerShell)

```powershell
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni $HOME/vimfiles/autoload/plug.vim -Force
```
![](image/psvimplug.png)
###### untuk lebih lanjut lagi kunjungi github:
```
https://github.com/junegunn/vim-plug/edit/master/README.md
```
#### 2. buat file configurasi vim di path $HOME extensi _vimrc atau _gvimrc
- buka vim ketik :echo $HOME disitulah file configurasi vim berada
- ketik :e _gvimrc atau :e _vimrc
![](image/gvimrc.gif)


