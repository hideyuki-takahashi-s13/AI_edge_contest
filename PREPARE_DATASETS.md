### Cityscapes Folder Structure

Cityscapesデータセットの構造をベースに、下記のようにデータを配置する。<br>
データは各リンク先よりダウンロードする。

```
Cityscapes
├── leftImg8bit_trainvaltest（画像データ　jpg形式）
│   ├── leftImg8bit
│   │   ├── train
│   │   │   ├── train_1
│   │   │   │   ├── train_00000.jpg
│   │   │   │   ├── train_00001.jpg
│   │   │   │   ├── ...
│   │   │   │　　
│   │   │   │   ```データリンク
│   │   │   │  　　https://drive.google.com/drive/folders/1Y6xPV-DEH11moTHszL_dKrvdCC0M4tPZ
│   │   │   │　　```
│   │   │   │
│   │   ├── val
│   │   │   ├── val_1
│   │   │   │   ├── train_1793.jpg
│   │   │   │   ├── train_1794.jpg
│   │   │   │   ├── ...
│   │   │   │
│   │   │   │   ```データリンク
│   │   │   │  　　https://drive.google.com/drive/folders/1Hcr7Z-utv16bnjleE6QpzSwHnPr85DrD
│   │   │   │　　```
│   │   │   │
│   │   ├── test(無し)
├── gtFine_trainvaltest（アノテーションデータ　png形式）
│   ├── gtFine
│   │   ├── train
│   │   │   ├── train_1
│   │   │   │   ├── train_00000.png
│   │   │   │   ├── train_00001.png
│   │   │   │   ├── ...
│   │   │   │　　
│   │   │   │   ```データリンク
│   │   │   │  　　https://drive.google.com/drive/folders/1bmxDijOytpfUsqJfNtkLWD_vRHBlRhZS
│   │   │   │　　```
│   │   │   │
│   │   ├── val
│   │   │   ├── val_1
│   │   │   │   ├── train_1793.png
│   │   │   │   ├── train_1794.png
│   │   │   │   ├── ...
│   │   │   │
│   │   │   │   ```データリンク
│   │   │   │  　　https://drive.google.com/drive/folders/1tOXxBJwdky2efwK5kTDrjJpcmQWCGOPr
│   │   │   │　　```
│   │   │   │
├───├───├── test(無し)
```
