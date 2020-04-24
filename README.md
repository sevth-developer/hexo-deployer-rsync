# 修改版

支持任意位置的私钥文件，不再局限于默认位置 `~/.ssh/id_rsa`

# hexo-deployer-rsync

[![Build Status](https://travis-ci.org/hexojs/hexo-deployer-rsync.svg?branch=master)](https://travis-ci.org/hexojs/hexo-deployer-rsync)
[![NPM version](https://badge.fury.io/js/hexo-deployer-rsync.svg)](https://www.npmjs.com/package/hexo-deployer-rsync)

Rsync deployer plugin for [Hexo].

## Options

You can configure this plugin in `_config.yml`.

``` yaml
deploy:
  type: rsync
  host: <host>
  user: <user>
  root: <root>
  key: <path/to/you/private_key>
  port: [port] # Default is 22
  delete: [true|false] # Default is true
  args: <rsync args>
  verbose: [true|false] # Default is true
  ignore_errors: [true|false] # Default is false
```

- **host**: Address of remote host  
- **user**: Username  
- **root**: Root directory of remote host   
- **port**: Port
- **delete**: Delete old files on remote host
- **args**: Rsync arguments
- **verbose**: Display verbose messages
- **ignore_errors**: Ignore errors
- **key**: you private key file path

## License

MIT

[Hexo]: http://hexo.io/
