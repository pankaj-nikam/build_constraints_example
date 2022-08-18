# Build Constraints in Golang

This example demonstrates how we can use build constraints in Golang.

Build constraints (ref: <https://pkg.go.dev/cmd/go#hdr-Build_constraints>) are a way to compile based on a constraint like for example you want to make sure that the build is only for developers, then you can build it specifically for developers using the flag.

To run the example:

    go run -tags prod .

This results in production build of the app.

If you don't pass anything, it results in development build
