
# Motivation

Hugo and Docsy make an excellent pairing for simple to maintain and publish
documentation.  Use this to get started.


# Prequisites

- [Install go](https://go.dev/doc/install)
- [Install hugo](https://gohugo.io/installation)

```
# I think this is simplest once you have go installed
go install -tags extended github.com/gohugoio/hugo@latest
```

# Build it

1. Clone it.
1. `rm go.mod go.sum`
1. `hugo mod init example.com/docs`
1. `hugo mod get github.com/google/docsy@v0.6.0`
1. `hugo mod tidy`
1. `npm install`
1. `hugo server`

Next steps: https://www.docsy.dev/docs/adding-content

# References

- https://github.com/gwatts/mostlydocs
- https://www.docsy.dev/
- https://github.com/OAI/OpenAPI-Specification/tree/main/examples/v3.0
