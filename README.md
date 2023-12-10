# @cord.network/setKey-api

This repo contains the file to setup the Session Keys on any validator machine after 'generate-session-keys'. As this doesnt need any UI, this is much friendlier to remote machines.


## Usage

```
$ yarn
$ export SESSIONKEYS="0xcd589e524dd4302e07a7df839abc8792c8994e91e9c5d790ebac7f86a6c1c6f4f0e196aac23e28c4363ee50d43e83da67ab714b30216b2cb898e5593d0f3873cf0e196aac23e28c4363ee50d43e83da67ab714b30216b2cb898e5593d0f3873cf0e196aac23e28c4363ee50d43e83da67ab714b30216b2cb898e5593d0f3873c"
$ export SECRET="0x1ef83609b52ffb52e926c10a2cb0e08d75d52698597c4f4da65ae872e38a4523"
$ yarn set-key
```

Only after the session-setKeys rpc call is made, the chain will consider the validator in the pool.


