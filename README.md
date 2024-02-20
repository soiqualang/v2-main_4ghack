# v2-main_4ghack
v2-main_4ghack

Nguồn: https://github.com/thuanht567/

## Code Termux (Chính):

```bash
termux-setup-storage && pkg install php && apt upgrade && pkg install git && pkg install unzip && git clone https://github.com/soiqualang/v2-main_4ghack  && clear && cd v2 && unzip v2.zip && chmod a+x 4ghack && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/v2"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/v2"' >> $HOME/.zshrc && source $HOME/.zshrc && exit
```

| - Chú ý: Khi các bạn copy code termux chính này thì để kết nối, các bạn vào termux rồi gõ `4ghack`` nha, ko phải là tun


## Code Termux (Dự Phòng): 

```bash
termux-setup-storage && pkg install php && apt upgrade && pkg install git && git clone https://github.com/soiqualang/vnw2-main_tun.git && clear && cd vnw2 && chmod a+x tun && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/vnw2"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/vnw2"' >> $HOME/.zshrc && source $HOME/.zshrc && exit
```

| -Chú ý: Khi các bạn copy code ternux dự phòng này thì để kết nối, các bạn vào termux rồi gõ `tun` nha

* Link tải Tun2Tap: https://play.google.com/store/apps/details?id=com.newtoolsworks.tun2tap&hl=vi
* Link tải HyperSocksDroid: https://drive.google.com/file/d/17YW17ak3FYUOxg1Z9BjeOYTj7cV1BLee/view?usp=sharing
* Link tải termux: https://play.google.com/store/apps/details?id=com.termux&hl=en_US&pli=1
Hoặc: https://drive.google.com/file/d/1d3LSKrS4mtQIe5q3hThh96nTQvsQ3V7L/view?usp=drivesdk

---

# Hướng dẫn đầy đủ

<details>
<summary>Hướng dẫn</summary>

## - Đối với code termux bản chính:

* Bước 1: Tải termux về và cài đặt, sau khi tải xong, mở nó lên.
* Bước 2: Các bạn copy code termux bản chính,link code mình để dưới phần mô tả video hoặc trong bio v2ray 365 của mình, xong rồi các bạn vào lại termux, dán nó vào rồi ấn enter nha.
Code:

```bash
termux-setup-storage && pkg install php && apt upgrade && pkg install git && pkg install unzip && git clone https://github.com/thuanht567/v2  && clear && cd v2 && unzip v2.zip && chmod a+x 4ghack && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/v2"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/v2"' >> $HOME/.zshrc && source $HOME/.zshrc && exit
```

* Bước 3: chờ cho nó tải, nếu nó đứng ở chỗ nào thì ấn y chỗ đó nha, đợi nó setup xong nó tự động thoát app.
* Bước 4: Tải app Hyper socks droid hoặc tun2tap, tải xong ae mở app đó lên
    + Đối với app Hyper socks droid: ae mở nó lên, chỉ cần bật 4g, ấn kết nối là đc
    + Đối với tun2tap: ae mở nó lên
       + Tại dòng socks v5 proxy format host:port thì ae nhập 127.0.0.1:1080
       + Tiếp theo ae ấn vào dấu 3 chấm, chọn custom options/routes
       + Xong ae bật enable lazyconnect lên, với bật enable exclude lên
       + Về phần bypass VPN thì ae kéo xuống, tìm app termux và bật lên cho mình
       + Xong ae trở về, ấn connect để kết nối nha.
* Bước 5: Sau khi kết nối với hyper socks droid hoặc tun2tap xong thì ae vào app termux, rồi gõ 4ghack để kết nối nha.

## - Đối với code termux bản dự phòng

| Nó cũng tương tự bản chính, chỉ khác mỗi cái lệnh nha: 

* Bước 1: Tải termux về và cài đặt, sau khi tải xong, mở nó lên.
* Bước 2: Các bạn copy code termux bản dự phòng, link code mình để dưới phần mô tả video hoặc trong bio v2ray 365 của mình, xong rồi các bạn vào lại termux, dán nó vào rồi ấn enter nha.
Code: 

```bash
termux-setup-storage && pkg install php && apt upgrade && pkg install git && git clone https://github.com/caotu2k5/vnw2.git && clear && cd vnw2 && chmod a+x tun && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/vnw2"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/vnw2"' >> $HOME/.zshrc && source $HOME/.zshrc && exit
```

* Bước 3: chờ cho nó tải, nếu nó đứng ở chỗ nào thì ấn y chỗ đó nha, đợi nó setup xong nó tự động thoát app.
* Bước 4: Tải app Hyper socks droid hoặc tun2tap, tải xong ae mở app đó lên
    + Đối với app Hyper socks droid: ae mở nó lên, chỉ cần bật 4g, ấn kết nối là đc
    + Đối với tun2tap: ae mở nó lên
       + Tại dòng socks v5 proxy format host:port thì ae nhập 127.0.0.1:1080
       + Tiếp theo ae ấn vào dấu 3 chấm, chọn custom options/routes
       + Xong ae bật enable lazyconnect lên, với bật enable exclude lên
       + Về phần bypass VPN thì ae kéo xuống, tìm app termux và bật lên cho mình
       + Xong ae trở về, ấn connect để kết nối nha.
* Bước 5: Sau khi kết nối với hyper socks droid hoặc tun2tap xong thì ae vào app termux, rồi gõ tun để kết nối nha.


Chúc các bạn thành công.
© Bản quyền thuộc về Hyper Networks.

</details>

