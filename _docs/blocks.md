---
title: Blocks
type: Specification
status: Draft
author: Onemorejsdeveloper
created: 2019-02-16
---

> This page describes endpoints for work with block information. List of endpoints is presents below.

## /api/blocks `GET`

Get information about all accounts

Parameters:

* generatorPublicKey 
* height 
* previousBlock 
* totalAmount 
* totalFee

<br/>

## /api/blocks/get?id={id} `GET`

Get block by ID

<br/>

## /api/blocks/getFee `GET`

Get blockchain fee

<br/>

## /api/blocks/getFees `GET`

Get blockchain fees schedule

<br/>

## /api/blocks/getReward `GET`

Get blockchain reward schedule

<br/>

## /api/blocks/getSupply `GET`

Get Total Supply of ADM Tokens 

<br/>

## /api/blocks/getHeight `GET`

Get Blockchain Height

<br/>

## /api/blocks/getStatus

Get status of height, fee, milestone, blockreward and supply

<br/>

## /api/blocks/getNethash `GET`

Get blockchain nethash

<br/>

## /api/blocks/getMilestone `GET`

Get blockchain milestone
