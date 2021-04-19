# mac-dev

## Introduction

This is an Ansible managed Mac Development environment.

## Setup

- Install brew
- Install openssl `brew install openssl`
- Open up venv
```
% python3 -m venv venv
% source venv/bin/activate
```
- Install ansible
```
# Brew environment variables
%  export LDFLAGS="-L/opt/homebrew/opt/openssl@1.1/lib"
% export CPPFLAGS="-I/opt/homebrew/opt/openssl@1.1/include"
% pip3 install ansible
```
