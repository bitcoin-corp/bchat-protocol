# bChat Protocol

**Token-gated chat rooms on BSV.** Every token already has a room: the room id is the token id, messages are ordinary [bSocial](https://pkg.go.dev/github.com/b-open-io/bsocial-overlay/bsocial) / [Bitcoin Schema](https://bitcoinschema.org/docs/schemas/messaging) channel messages, membership is holding the token, and an invite is sending one.

- Read the spec: [SPEC.md](SPEC.md) (Draft 0.1)
- Reference implementations: bWallet (mobile wallet) and bChat (bitcoinchat.online)
- Built on bSocial, Bitcoin Schema, bmap, 1Sat Ordinals and BAP — see Acknowledgements in the spec.

Status: draft for comment. Open an issue for questions, objections and proposals; pull requests welcome.

Published by The Bitcoin Corporation Ltd. MIT licensed.
