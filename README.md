# リポジトリの概要
torch7のテスト用。2015年3月30日作成。
主な使用者は岩澤

# torchについて
公式サイトより抜粋。印象値としてはパッケージを入れることでかなり柔軟にいろんなことができる。
逆にパッケージに依存してるとも言える。

>The goal of Torch is to have maximum flexibility and speed in building your scientific algorithms while making the process extremely simple. Torch comes with a large ecosystem of community-driven packages in machine learning, computer vision, signal processing, parallel processing, image, video, audio and networking among others, and builds on top of the Lua community.

>At the heart of Torch are the popular neural network and optimization libraries which are simple to use, while having maximum flexibility in implementing complex neural network topologies. You can build arbitrary graphs of neural networks, and parallelize them over CPUs and GPUs in an efficient manner.


# Install手順
torchサイトないのGetting Startedに従う。Ubuntu14.04環境上で動作確認。

* [torch Getting tarted](http://torch.ch/docs/getting-started.html#_)
* bashじゃないシェル使ってる人は適宜読み替える。
* GPU使うときはたぶんCudaのインストール必要（インストールしてある環境でやってしまったのでよくわからない）　

# Tutorial, Demo
torchのcheatsheet内にあるTutorialとDemoをやる。
動かすのは単純。ただ、チュートリアルにしてはコードが長い印象。

* [Toch Cheatsheet](https://github.com/torch/torch7/wiki/Cheatsheet)

# Convolutional Layer関連
実装がたくさんある。nn, cudnn, dpなど。
* [nn](https://github.com/torch/nn)
* [cudnn](https://github.com/soumith/cudnn.torch)
* [dp](http://dp.readthedocs.org/en/latest/index.html): Pylearn2に近い記法。
* [ベンチマーク](https://github.com/soumith/convnet-benchmarks): theanoとかとも比較されている

# 参考サイト
### Luaの説明
1. [[Lua Style Guide](http://lua-users.org/wiki/LuaStyleGuide)]
2. [[Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/)]
2. [[どっかのサイト](http://d.hatena.ne.jp/toromoti/20101124/1290573102)]
3. ぱっと見の印象は、「なんでもあり」「Rubyっぽい」「と思いきやJSっぽい」

### torch関連
1. [[Torch7の分かりにくい話](http://ultraist.hatenablog.com/entry/2015/01/30/221102)]

