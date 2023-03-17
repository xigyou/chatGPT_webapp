chatgpt-webapp
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

**Deploy a webapp chatbot of chatGPT with openAI API Key and gradio.**

*You may need two things below, for Chinese people I’ll list the
tutorial at the end:* 1. An openAI API Key, maybe a VPN to apply one 2.
A credit card not applied in China sovereign area if big usage is
expected

## Install

``` sh
mamba install -c conda-forge openai gradio fire

git clone https://github.com/DanXu-git/chatGPT_webapp
```

## How to use

``` sh
cd chatGPT_webapp

export OPENAI_API_KEY=$your_openAI_key

chatgpt_webapp/chatGPT_webapp.py \
--IP [your server IP, e.g 0.0.0.0] \
--Port 5010[default] \
--model_engine 'gpt-3.5-turbo'[default]

chatGPT_webapp.py --help # for usage
```

GitHub Page Document:  
https://danxu-git.github.io/chatGPT_webapp/

## for Chinese user, 中国用户指引

[注册openAI账号教程链接](https://sms-activate.org/cn/info/ChatGPT)

申请openAI API Key:  
\>登陆账号后点击右上角personal个人头像 -\> View API keys -\> create new
secret key,  
\>复制key创建一个环境变量， export OPENAI_API_KEY=\$your_key

申请虚拟信用卡(API key有免费额度，超出支付用):
[https://depay.depay.one](https://depay.depay.one/web-app/register-h5?invitCode=536282&lang=en-us)
