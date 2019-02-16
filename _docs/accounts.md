---
title: Accounts
type: Specification
status: Draft
author: Onemorejsdeveloper
created: 2019-02-16
---

> This page describes endpoints for work with account information. List of endpoints is presents below.

## /api/accounts `GET`

Get information about all accounts

<br/>

## /api/accounts/open `POST`

Get information about all accounts

Request body:
```$json
{ "secret": "secret key of account" }
```

<br/>

## /api/accounts?address={address} `GET`

Get account information from address

<br/>

## /api/accounts/getBalance?address={address} `GET`

Get account balance

<br/>

## /api/accounts/getPublicKey?address={address} `GET`

Get account public key

<br/>

## /api/accounts/generatePublicKey `POST`

Generate public key

<br/>

## /api/accounts/delegates?address={address} `GET`

Get vote data of an account

<br/>

## /api/accounts/delegates `PUT`

Vote delegates