This repository contains generated golang code for:
* Event Family: https://desp.kroger.com/event-family/__EFID__
* Version: v0.0.7

To use this in your go client, add the following requirements to your go.mod file.

```
module github.com/krogertechnology/my-go-client-application

go 1.13

require (
	github.com/actgardner/gogen-avro/v9 v9.0.0 // indirect
	robhoeting-kr/desp-catalog-go-my-group-my-artifact v0.0.7
	...
```