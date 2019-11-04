# LKY's Golang Study

### 2019.11.5(Mon)

今天一早 VSCode 給我推薦安裝了這些包，我要來看他們到底是什麼

```
gocode
  gopkgs
  go-outline
  go-symbols
  guru
  gorename
  gotests
  gomodifytags
  impl
  fillstruct
  goplay
  godoctor
  dlv
  gocode-gomod
  godef
  goreturns
  golint
```

### 2019.11.1(Fri)

- 編譯語言居然有當直譯用的模式，go run hello.go 就可以用了，太神奇了。這樣不論是在學習或使用都方便很多。
- Go 語法與 Python 相似的地方很多，寫起來非常像。
- Go 特別的地方
    - import 了沒用到的包、或宣告了沒用到的變數，都會無法通過編譯，其他語言都只是 warning。
    - 型別是宣告在變數的後面，這是第一次看到。
    - 對括號位置有強制性要求（這比 Python 只用縮排劃出 scope 可讀性好多了）
    - 對「:=」這個神秘的運算子還不太了解，希望找到書能講的清楚一些。
