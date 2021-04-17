# PTCG Flip Coin

![](ptcg_flip_coin.gif)

## Requirements

- Swift 5.3 Later

## About

コインを投げて表・裏のどちらかを判定するためのモジュールです

## How to use

### PTCGFlipCoin.flip()

コインを1回投げ、その結果を返します

```swift
PTCGFlipCoin.flip() // => .heads or .tail
```

### PTCGFlipCoin.repeatWith()

指定した数だけ繰り返しコインを投げ、その結果をまとめて返します

```swift
PTCGFlipCoin.repeatWith(3) // => e.g. [.heads, .tail, .heads]
```

### PTCGFlipCoin.repeatUntil(.heads or .tail)

指定したコインの向きが出るまで繰り返しコインを投げ、その結果をまとめて返します

```swift
PTCGFlipCoin.repeatWith(.tail) // => e.g. [.heads, .heads, .tail]
```