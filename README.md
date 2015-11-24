# Holmes-Totem-Service-VTSample

## Description

A very simple Holmes-Totem service which'll collect everyting Virustotal knows about a sample.
It can also upload unknown samples to Virustotal.

## Usage

Download the only dependencie, httprouter:
```bash
go get github.com/julienschmidt/httprouter
```
Edit `main.go` and fill in the constants with your own values.
```go
const (
	ApiKey               = "APIKEY"
	UploadUnknownSamples = true
	HttpBinding = ":7710"
)
```
Start the server by using `go run`, `go build` or `go install`, whatever you prefer.