# Sound_related_ofxAddons
サウンド関連のofxAddonの調査状況

## 実行環境
- Windows10 64bit
- VisualStudio2022
- of_v0.11.2_vs2017_release

### ofxDStudio/ofxDasySP
- コンパイル不可

### ofxATK
- 64bitではコンパイル不可
- 32bitではコンパイル可能
- Reverbを再生した結果音割れが激しい

### ofxSoundObject 
- コンパイル可能
- Reverbは無い

### ofxTonic
- 未調査

### ofxFmod3DSoundPlayer
- コンパイル可能
- Reverbは無い
- XY軸に対応して音像の位置が動く

### ofxMaxim
- https://github.com/rychrd/ofxMaxim.git
- このリポジトリでコンパイル可能

### ofxReverb
- コンパイル可能（Releaseのみ）

### ofxPDSP
- 未調査
