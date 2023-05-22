# Minecraft-Sneak and firework
![Minecraft-firework](https://github.com/n-tsuyoshi/sample/assets/133200934/ae93bbe1-6099-40c1-b6b1-048e334b7454)
## 使用言語
Java

## 工夫した点
しゃがみ込んだ際に花火が上がるように、`if(count % 2 == 0)`と記載しました。

以下、実際のコード

https://github.com/n-tsuyoshi/sample/blob/5df08e9fb066a3220b23483adf8d2ac6a1c488be/src/main/java/plugin/sample/Main.java#LL38C5-L75C6

また、`onPlayerBedEnter`にてベッドに寝ようとするとレベルが「30」になる、チートを作成しました。

以下、実際のコード

https://github.com/n-tsuyoshi/sample/blob/a636ad6658e25ee6595aebca0fde52c15342e464/src/main/java/plugin/sample/Main.java#LL77C5-L87C1

## ハマった点
`if`で実際にどんな条件分岐にすればしゃがんだ時だけ花火を挙げられるかを考えるのが難しかったですが、

実際にGoogleで調べて学んでいくうちに少し、条件分岐について理解することができて表現することができました。

## 開発した環境
Minecraft ver.1.19.4

JDK ver.Oracle OpenJDK 17.0.7
