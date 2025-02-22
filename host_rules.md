# 支持的网站列表
具体哪些域名使用了域前置，哪些可以通过cloudflare workers/pages转发，请看[hosts.source.txt](./hosts.source.txt)。

- 维基媒体
- google
- github
- duckduckgo
- twitter
- pixiv
- quora
- flickr
- onedrive
- reddit
- instagram
- openai

## 电信网络
```
--host-rules="MAP upload.wikimedia.org upload.wikimedia.org:443, MAP *.wikipedia.org wikivoyage.org:443, MAP wikimedia.org wikivoyage.org:443, MAP *.wikimedia.org wikivoyage.org:443, MAP google.com www.gstatic.cn:443, MAP youtube.com www.gstatic.cn:443, MAP *.google.com www.gstatic.cn:443, MAP *.gstatic.com www.gstatic.cn:443, MAP *.googleapis.com www.gstatic.cn:443, MAP *.googleusercontent.com www.gstatic.cn:443, MAP *.ytimg.com www.gstatic.cn:443, MAP *.youtube.com www.gstatic.cn:443, MAP *.ggpht.com www.gstatic.cn:443, MAP github.com octocaptcha.com:443, MAP gist.github.com octocaptcha.com:443, MAP github.githubassets.com www.yelp.com:443, MAP *.githubusercontent.com www.yelp.com:443, MAP duckduckgo.com duck.com:443, MAP *.duckduckgo.com duck.com:443, MAP twitter.com tweetdeck.com:443, MAP *.twitter.com tweetdeck.com:443, MAP *.twimg.com www.yelp.com:443, MAP pixiv.net fanbox.cc:443, MAP *.pixiv.net fanbox.cc:443, MAP *.pximg.net pximg.net:443, MAP quora.com qr.ae:443, MAP *.quora.com qr.ae:443, MAP identity.flickr.com flic.kr:443, MAP flickr.com combo.staticflickr.com:443, MAP *.flickr.com combo.staticflickr.com:443, MAP onedrive.live.com od0.live.com:443, MAP skyapi.onedrive.live.com od0.docs.live.net:443, MAP reddit.com www.yelp.com:443, MAP *.reddit.com www.yelp.com:443, MAP *.redd.it www.yelp.com:443, MAP *.redditmedia.com www.yelp.com:443, MAP *.redditstatic.com www.yelp.com:443, MAP instagram.com igsonar.com:443, MAP *.instagram.com igsonar.com:443, MAP *.cdninstagram.com igsonar.com:443, MAP api.openai.com platform.openai.com:443" --host-resolver-rules="MAP upload.wikimedia.org 103.102.166.240, MAP wikivoyage.org 208.80.153.224, MAP www.gstatic.cn 106.75.251.36, MAP octocaptcha.com 20.27.177.113, MAP www.yelp.com 151.101.40.116, MAP duck.com 20.43.161.105, MAP tweetdeck.com 104.244.45.4, MAP www.yelp.com 151.101.40.116, MAP fanbox.cc 210.140.131.221, MAP pximg.net 210.140.139.136, MAP qr.ae 107.20.115.65, MAP flic.kr 34.231.89.51, MAP combo.staticflickr.com 13.35.66.99, MAP od0.live.com 13.107.42.13, MAP od0.docs.live.net 13.105.28.18, MAP www.yelp.com 151.101.40.116, MAP igsonar.com 31.13.66.167, MAP platform.openai.com 52.152.96.252"
```

## 其他网络
```
--host-rules="MAP upload.wikimedia.org upload.wikimedia.org:443, MAP *.wikipedia.org wikivoyage.org:443, MAP wikimedia.org wikivoyage.org:443, MAP *.wikimedia.org wikivoyage.org:443, MAP google.com www.gstatic.cn:443, MAP youtube.com www.gstatic.cn:443, MAP *.google.com www.gstatic.cn:443, MAP *.gstatic.com www.gstatic.cn:443, MAP *.googleapis.com www.gstatic.cn:443, MAP *.googleusercontent.com www.gstatic.cn:443, MAP *.ytimg.com www.gstatic.cn:443, MAP *.youtube.com www.gstatic.cn:443, MAP *.ggpht.com www.gstatic.cn:443, MAP github.com octocaptcha.com:443, MAP gist.github.com octocaptcha.com:443, MAP *.githubusercontent.com github.githubassets.com:443, MAP duckduckgo.com duck.com:443, MAP *.duckduckgo.com duck.com:443, MAP twitter.com tweetdeck.com:443, MAP *.twitter.com tweetdeck.com:443, MAP *.twimg.com github.githubassets.com:443, MAP pixiv.net fanbox.cc:443, MAP *.pixiv.net fanbox.cc:443, MAP *.pximg.net pximg.net:443, MAP quora.com qr.ae:443, MAP *.quora.com qr.ae:443, MAP identity.flickr.com flic.kr:443, MAP flickr.com combo.staticflickr.com:443, MAP *.flickr.com combo.staticflickr.com:443, MAP onedrive.live.com od0.live.com:443, MAP skyapi.onedrive.live.com od0.docs.live.net:443, MAP reddit.com github.githubassets.com:443, MAP *.reddit.com github.githubassets.com:443, MAP *.redd.it github.githubassets.com:443, MAP *.redditmedia.com github.githubassets.com:443, MAP *.redditstatic.com github.githubassets.com:443, MAP instagram.com igsonar.com:443, MAP *.instagram.com igsonar.com:443, MAP *.cdninstagram.com igsonar.com:443, MAP api.openai.com platform.openai.com:443" --host-resolver-rules="MAP upload.wikimedia.org 103.102.166.240, MAP wikivoyage.org 208.80.153.224, MAP www.gstatic.cn 106.75.251.36, MAP octocaptcha.com 20.27.177.113, MAP github.githubassets.com 185.199.108.154, MAP duck.com 20.43.161.105, MAP tweetdeck.com 104.244.45.4, MAP github.githubassets.com 185.199.108.154, MAP fanbox.cc 210.140.131.221, MAP pximg.net 210.140.139.136, MAP qr.ae 107.20.115.65, MAP flic.kr 34.231.89.51, MAP combo.staticflickr.com 13.35.66.99, MAP od0.live.com 13.107.42.13, MAP od0.docs.live.net 13.105.28.18, MAP github.githubassets.com 185.199.108.154, MAP igsonar.com 31.13.66.167, MAP platform.openai.com 52.152.96.252"
```
