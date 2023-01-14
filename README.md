# Golang URL Shortener

// Forked from mxschmitt/golang-url-shortnened - code has been abandoned for several years
// Copyright where applicable

[![GoDoc](https://godoc.org/github.com/acacio/url-shortener?status.svg)](https://godoc.org/github.com/acacio/url-shortener)
[![Go Report Card](https://goreportcard.com/badge/github.com/acacio/url-shortener)](https://goreportcard.com/report/github.com/acacio/url-shortener)
[![Coverage Status](https://coveralls.io/repos/github/acacio/url-shortener/badge.svg?branch=master)](https://coveralls.io/github/acacio/url-shortener?branch=master)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Docker Pulls](https://img.shields.io/docker/pulls/acacio/url_shortener.svg)](https://hub.docker.com/r/acacio/url_shortener/)

## Main Features

- URL Shortening
- Visitor Counting
- Expirable Links
- URL deletion
- Multiple authorization strategies:
    - Local authorization via OAuth 2.0 (Google, GitHub, Microsoft, and Okta)
    - Proxy authorization for running behind e.g. [Google IAP](https://cloud.google.com/iap/)
- Easy [ShareX](https://github.com/ShareX/ShareX) integration
- Dockerizable
- Multiple supported storage backends
    - High performance local database with [bboltdb](https://github.com/etcd-io/bbolt)
    - Persistent non-local storage with [redis](https://redis.io/)

## [Webinterface](https://so.sh0rt.cat)

![Short URLs](https://user-images.githubusercontent.com/17984549/32700384-955d9336-c7c4-11e7-9fab-4141a86a375c.png)

---

![Generate ShareX Configuration](https://user-images.githubusercontent.com/17984549/32700395-cf9f057a-c7c4-11e7-9d2b-7523c8a95a20.png)

## Documentation

- [Installation](https://github.com/acacio/url-shortener/wiki/Installation)
- [Configuration](https://github.com/acacio/url-shortener/wiki/Configuration)
- [Setting up OAuth](https://github.com/acacio/url-shortener/wiki/Setting-up-OAuth)
- [ShareX Usage](https://github.com/acacio/url-shortener/wiki/ShareX)

## Why did you built this

Only because I just want to extend my current self hosted URL shorter (which was really messy code) with some more features and learn about new techniques like:

- Golang unit testing
- React
- Makefiles
- Travis CI
- Key / Value databases
- Dockerfile and Docker Image Creation
