# PyFeishu

[![GitHub issues](https://img.shields.io/github/issues/liukecode/pyfeishu)](https://github.com/liukecode/pyfeishu/issues)
[![GitHub forks](https://img.shields.io/github/forks/liukecode/pyfeishu)](https://github.com/liukecode/pyfeishu/network)
[![GitHub stars](https://img.shields.io/github/stars/liukecode/pyfeishu)](https://github.com/liukecode/pyfeishu/stargazers)
[![GitHub license](https://img.shields.io/github/license/liukecode/pyfeishu)](https://github.com/liukecode/pyfeishu/blob/main/LICENSE)
[![contributors](https://img.shields.io/github/contributors/liukecode/pyfeishu)](https://github.com/liukecode/pyfeishu/graphs/contributors)
[![PyPI](https://img.shields.io/pypi/v/pyfeishu)](https://pypi.org/project/pyfeishu/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pyfeishu)](https://pypi.org/project/pyfeishu/)
[![Downloads](https://pepy.tech/badge/pyfeishu/month)](https://pepy.tech/project/pyfeishu)

This is a msg-robot for [feishu](https://open.feishu.cn/document/uAjLw4CM/ukTMukTMukTM/reference/im-v1/introduction)

## Install
```
python -m pip install pyfeishu
```
## Getting Started
send text msg
```
import pyfeishu
bot = pyfeishu.FeishuBot(app_id, app_secret)
fs.send_text("test text"))
```

send image msg
```
image_key = bot.upload_image("img_path")
bot.send_image(image_key, groups='oc_foo')
```

## Features
- Automatically token management
- Cache embeded


## Contributing

Contributions are welcome.<br/>
If you've found a bug within this project, please open an issue to discuss what you would like to change.<br/>
If it's an issue with the API, please report any new issues at [pyfeishu issues](https://github.com/liukecode/pyfeishu)