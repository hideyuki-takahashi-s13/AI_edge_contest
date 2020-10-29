### Cityscapes Folder Structure

Cityscapesデータセットに合わせ、下記構造でデータを配置する。
データは

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
│   │   │   │   ```bash
│   │   │   │  　　> !wget https://drive.google.com/drive/folders/1Y6xPVDEH11moTHszL_dKrvdCC0M4tPZ?usp=sharing
│   │   │   │　　```
│   │   │   │
│   │   ├── val
│   │   │   ├── val_1
│   │   │   │   ├── train_1793.jpg
│   │   │   │   ├── train_1794.jpg
│   │   │   │   ├── ...
│   │   │   │
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
│   │   │   │
│   │   ├── val
│   │   │   ├── val_1
│   │   │   │   ├── train_1793.png
│   │   │   │   ├── train_1794.png
│   │   │   │   ├── ...
│   │   │   │
│   │   │   │
│   │   ├── test(無し)
```
