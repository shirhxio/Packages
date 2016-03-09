# Packages
packages of Unity(particles, cursor, etc...)
Unity 5.3.2p3
またどこかしらで再利用できればいいのだけれど...

* beamparticle.unitypackage
パーティクルの練習。
ビームの主軸部分とそれを追従する部分がある。ともに回転してるので、主軸の数を増やしてみるのも面白い。
軸からの距離なども変えられます。

* handcursor.unitypackage
上下運動の最上部で指先の指す位置はtransform.position(初期は)であり、配置してる指先の位置でないことに注意。
位置を変えるときはSetPos(float x, float y)を使うこと。
上下運動の幅や周期は変えられます。
一応、絵も自分で書いたものなのでご安心を。

* savepoint.unitypackage
パーティクルの練習その２。それはそれっぽく出来てます。
Trailが二種類付いているので不必要な方をprefabから消してください。
回転する速さや球の数も変えられます。
