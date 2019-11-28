
# Modifications:

This is standard golang oauth2 library with one modification: http dump added. 
Meant to be used for debug purposes.

# OAuth2 for Go

[![Build Status](https://travis-ci.org/golang/oauth2.svg?branch=master)](https://travis-ci.org/golang/oauth2)
[![GoDoc](https://godoc.org/github.com/sgumirov/oauth2?status.svg)](https://godoc.org/github.com/sgumirov/oauth2)

oauth2 package contains a client implementation for OAuth 2.0 spec.

## Installation

~~~~
go get github.com/sgumirov/oauth2
~~~~

Or you can manually git clone the repository to
`$(go env GOPATH)/src/github.com/sgumirov/oauth2`.

See godoc for further documentation and examples.

* [godoc.org/github.com/sgumirov/oauth2](http://godoc.org/github.com/sgumirov/oauth2)
* [godoc.org/github.com/sgumirov/oauth2/google](http://godoc.org/github.com/sgumirov/oauth2/google)

## Policy for new packages

We no longer accept new provider-specific packages in this repo. For
defining provider endpoints and provider-specific OAuth2 behavior, we
encourage you to create packages elsewhere. We'll keep the existing
packages for compatibility.

## Report Issues / Send Patches

This repository uses Gerrit for code changes. To learn how to submit changes to
this repository, see https://golang.org/doc/contribute.html.

The main issue tracker for the oauth2 repository is located at
https://github.com/golang/oauth2/issues.
