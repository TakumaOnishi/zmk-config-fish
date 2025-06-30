# おさかなキーパッド  
これは、[おさかなキーボード](https://o24.works/fish/)左手デヴァイスエディションのためのZMK Firmareの設定リポジトリです。  
キーマップを書き換えておさかなを更新する手順は[ユーザーガイド](https://o24.works/fish/guide/)を参照してください。  
  
## 書き換えていいファイル  
### [fish.keymap](config/boards/shields/fish/fish.keymap)  
キーの割り当てや入力の内容を設定できます。このファイルを視覚的に編集できる[キーマップエディター](https://o24.works/fish/editor/)も活用してください。  
### [fish.conf](config/boards/shields/fish/fish.conf)  
スリープ時間、検出名など、キーボード本体の挙動を設定できます。  
### [Kconfig.defconfig](config/boards/shields/fish/Kconfig.defconfig)
親機の左右を変えることができます。  
