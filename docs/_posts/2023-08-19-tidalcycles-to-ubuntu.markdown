---
layout: post
title:  "TidalCyclesをUbuntuにインストールする"
date:   2023-08-19 12:36:48 +0900
categories: tidalcycles ubuntu
---
TidalCyclesをUbuntu似インストールするのはとてもかんたんで、ブートストラップですんなり行けばそのまま動く。  
ただし、オーディオインターフェースを使用するときにはSuperColliderから出力を設定することが難しいので、Jackを使用する必要がある。  
今回はJackのGUI版であるQJackCtlを使用して出力先を変更している。