# slack-reaction-award
めっちゃいい投稿が何かを賞として投稿するスクリプトです。
全部で4部門を適当に用意して適当に投稿します。

---

This script calculates Slack-Reactions of your work space, and get the `best post`.

There are three categories,

1. Award for Omoro (lough)
1. Award for Variety (number of reaction various)
1. Award for Amount (number of reaction amount)
1. Award for Thanked (number of reaction like thanked one)

## How to run
1. `vim _tools/local/config.toml`

```
[slack]
  token  = "xoxp-***"
  year = 2020
  post_channel = "ABC***"
```

Set slack bot authentications and channel_ID to post messages

2. Do: `go run cmd/app/main.go`