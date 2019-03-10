### go-humanize
---
https://github.com/dustin/go-humanize

```go
fmt.Printf("That file is %s.", humanize.Bytes(82854982))

fmt.Printf("This was touched %s.", humanize.Time(someTimeInstance))

fmt.Printf("You're my %s best friend.", humanize.Ordinal(193))

fmt.Printf("You owe $%s.\n", humanize.Comma(6582491))

fmt.Printf("%f", 2.24)
fmt.Printf("%s", humanize.Ftoa(2.24))
fmt.Printf("%f", 2.0)
fmt.Printf("%s", humanize.Ftoa(2.0))

humanize.SI(0.0000000223, "M")

english.PluralWord(1, "object", "")
english.PluralWord(42, "object", "")
english.PluralWord(2, "bus", "")
english.PluralWord(99, "locus", "loci")

english.Plural(1, "object", "")
english.Plural(42, "object", "")
english.Plural(2, "bus", "")
english.Plural(99, "locus", "loci")

english.WordSeries([]string{"foo"}, "and")
english.WordSeries([]string{"foo", "bar"}, "and")
english.WordSeries([]string{"foo", "bar", "baz"}, "and")

english.OxfordWordSeries([]string{"foo", "bar", "baz"}, "and")
```

```
```

```go
// https://godoc.org/github.com/dustin/go-humanize#pkg-subdirectories
```
