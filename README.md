# KF8253 - 8253-like programmable interval timer written in SystemVerilog

## 概要
SystemVerilogで書いた8253のようなものです。
オリジナルとはクロック同期で動作するなどの違いがあります。

そのためカウンタの入力幅など特性がデバイスや入力するメインクロックによって変化することに注意してください。

シュミレータで動作を確認しましたが、FPGAへコンフィグレーションして確認を行ってはいません。

