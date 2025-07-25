## Raspberry Pi用OS Raspberry Pi OSのインストール

1) Class10のmicroSD(8～32G)を用意します。  
*64GB以上のSDカードの場合、exFATでフォーマットされます。
Raspberry Pi OSはexFATに対応していませんので、別のツールを使ってFAT16またはFAT32でフォーマットする必要があります。*

2) SDカード用フォーマッターとユーザーマニュアルをダウンロードします。  
SDアソシエーションのダウンロードページから'SDメモリカードフォーマッター'と'ユーザーマニュアル'をダウンロードします。
https://www.sdcard.org/jp/downloads/formatter_4/index.html

　　　eMMCへOSをインストールする場合は、USB micro-B 書込み設定用3PINコネクタの[1-2]をショート(有効)にして書込む必要があります。  
  　　　詳しくは下記URLの「Set up the host device」をご参照ください。  
     　　　https://www.raspberrypi.com/documentation/computers/compute-module.html

4) 'SDメモリカードフォーマッター'を使って、SDカードをフォーマットします。
ファーマット方法につきましては、ダウンロードしたユーザーマニュアルをご参照ください。

5) Raspberry財団公式ホームページよりRaspberry Pi Imager をダウンロードしてインストールします。https://www.raspberrypi.com/software/

6) Raspberry Pi OSをインストールします。
  

Raspberry Pi Imagerを起動し、「Raspberry Piデバイス」「OS」「ストレージ」を選択し「次へ」をクリックします。  

![RasPiInstall 01](/Image/RasPiImager_pic/RasPiInstall_01.png)  

事前にRapberry Piの設定をする場合は「設定を編集する」をクリックします。後から設定する場合は「いいえ」をクリックします。

![RasPiInstall 02](/Image/RasPiImager_pic/RasPiInstall_02.png)  

OSの書込みを続行する場合は「はい」をクリックします。  

![RasPiInstall 03](/Image/RasPiImager_pic/RasPiInstall_03.png)  

以上でRaspberry Pi OSのインストールは完了です。  

![RasPiInstall 04](/Image/RasPiImager_pic/RasPiInstall_04.png)
