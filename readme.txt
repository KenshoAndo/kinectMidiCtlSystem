kinectMidiCtlSystem readme

準備
１．SimpleOpenNI,oscP5ライブラリをProcessingにインストール
２．Kinectを接続し、Hands3d.pdeを起動
３．osc2midi.maxpatを起動
４．ctloutをfrom Max Rantime 1に設定
５．Live（ver8以降）を起動、FilterCtlDemoかMixerCtlDemoプロジェクトを開く
６．Live環境設定の[MIDI/Sync]タブで、Inputにfrom Max 1を選択、トラックとリモートをオンに

使い方
１．Kinectの前で手を軽く振り、赤い点が出れば手の認識ができています
２．Maxのチェックボックスをオンにすると、手のx, y, z座標に応じてパラメータが変化します
３．３つのチェックタブで、操作するパラメータのセットを切り替えることができます
４．操作するパラメータを切り替えるときは、LiveのMIDIマップモードを使用し、Max上のスライダでアサインを行ってください。

FilterCtlDemoではEQの周波数・ゲイン・Qが、
MixerCtlDemoではトラックのパン・フェーダー・センドが、それぞれx, y, zにアサインされています。