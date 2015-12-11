
## reference

- http://make.bcde.jp/category/27/

## prepare

- 赤外線リモコン受信モジュール
- 赤外線LED
- トランジスタ（赤外線出力増幅用）
- bread board
- 抵抗

## install

sudo apt-get install lirc

（lirc_rpiを使えるように設定する。）

sudo modprobe lirc-rpi gpio_in_pin=24 gpio_out_pin=25


