# AnimationClipInspectorExtension
AnimationClipのInspectorをルールベースで適応するオブジェクトを変えるEditor拡張です。

※本プロジェクトでは Relfectionを利用して呼び出しを行っています。<br />
　そのため、Unityのバージョンによっては動作しない可能性があります。<br />
<br />
　動作確認バージョン: 2017.2 / 2017.3 / 2018.1β<br />

## 動作の様子
![alt text](doc/demo.gif)

上のWindowで指定したルールに沿って、AnimationClipのPreviewで適応するGameObjectを変更しています。<br />
Windowが存在している間は、このルールに沿って AnimationClipのPreviewのモデルを変更します。<br />

## ファイルについて
本体は Assets/Editor/AnimationClipInspectorExtention.cs にあります。<br />
またプロジェクト直下に AnimationClipInspectorExtention.json という形で適応するルールを保存しています

## 謝辞
本プロジェクトのサンプルとして、UnityChanのデータを利用しています<br />

![alt text](doc/imageLicenseLogo.png)

この作品はユニティちゃんライセンス条項の元に提供されています
c UTJ/UCL


