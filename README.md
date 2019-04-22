[![Build Status](https://api.travis-ci.org/guilhermeor/simple-blockchain.png)](https://travis-ci.org/guilhermeor/simple-blockchain)

# simple-blockchain

Blockchain using golang

## Techs:
- Go 1.12.4

## How to run:

```bash
go run main.go
```

## Endpoints

| Route | Verb | Description |
| --- | --- | --- |
| `http://localhost:8080` | GET | List all blocks from chain |
| `http://localhost:8080` | POST | Post a new message |

The message sent should be like:

```json
{"BPM":12}
```
Code based on this [article](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc).
