# My Tutorial

```ghost
レゴブロック.まえ()
レゴブロック.うしろ()
レゴブロック.ぶらんぶらん()
input.onButtonPressed(Button.A, function () {
	
})
```

## Step 1

Aボタンをおすとおさるさんがまえにくるようにしてみよう

```blocks
input.onButtonPressed(Button.A, function () {
	レゴブロック.まえ()
})
```

## Step 2

Bボタンをおすとおさるさんがうしろにいくようにしてみよう

```blocks
input.onButtonPressed(Button.A, function () {
	レゴブロック.うしろ()
})
```

## step 3

AボタンとBボタンをいっしょにおすとおさるさんがぶらんぶらんするようにしてみよう

```blocks
input.onButtonPressed(Button.AB, function () {
    レゴブロック.ぶらんぶらん()
})
```

## step 4

よくできました！

