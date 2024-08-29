# holiday_jp-go

[![GoDoc](https://godoc.org/github.com/holiday-jp/holiday_jp-go?status.svg)](https://godoc.org/github.com/holiday-jp/holiday_jp-go) [![test](https://github.com/holiday-jp/holiday_jp-go/workflows/test/badge.svg)](https://github.com/holiday-jp/holiday_jp-go/actions)

🎌 Japanese holiday for Go

## Requirements
* go 1.9 or later

## Installing

```bash
$ go get github.com/IdaliaGeeks/holiday_jp-go
```

## Example

```go
import "github.com/IdaliaGeeks/holiday_jp-go"

if holiday.IsHoliday(time.Now()) {
    fmt.Println("today is holiday!")
}
```
