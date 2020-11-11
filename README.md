# PhosPM: Phos Private Message

Recently someone contacted me on github, by opening an issue.

I had to reply him (her) with a message showing my email, visible to all, which I then deleted after he (she) responded.

Hence the need of PhosPM &mdash; using public key to encode a message intended for the recipient.

In fact, this idea is not new and numerous programs have been written to do that.

The problem is exactly that &mdash; need to install those programs.

PhosPM is a completely web based solution &mdash; and beyond!


## How to use PhosPM

1. Open JSEncrypt demo page:

- https://travistidwell.com/jsencrypt/demo/

2. Generate your own private public key pair. Save your private key and do not expose it. You may regenerate another private public key pair any time.

3. Leave your public key in a public forum / post.

4. Let the sender of message use your public key to encode the message, and post it in the public forum / post.

5. Decrypt the message using your private key.

6. Example &mdash; This is my public key generated as of the time stamp of this README.md:

```
-----BEGIN PUBLIC KEY-----
MIGeMA0GCSqGSIb3DQEBAQUAA4GMADCBiAKBgHYkAEjsigRm37mLHwi5U76sPFmN
HceiLnoK6FUUGG48z48bHcaPTHKJmlh6xx68fktVmdVSwKY1i5B6w2Ehlr4Ih7Re
eSnd4E6kkC0ycB1k2rKnVethj+LEWaX6+xurZvRgN+ebxmX5h7cpzseF/ftYpbn5
WH5OONCPJOzhdGwNAgMBAAE=
-----END PUBLIC KEY-----
```

## Beyond Private Messages

PhosPM is not just about private messages using JSEncrypt demo page.

See the following for further work:

1. bit.do/PhosDUA (short URL for the page below)

- https://github.com/udexon/XIDT/blob/master/Greet_Secret_Phrase.md

2. https://github.com/udexon/PhosPay
