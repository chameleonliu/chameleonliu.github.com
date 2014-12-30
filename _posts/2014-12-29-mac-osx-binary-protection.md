---
layout: post
title: "Mac OSX Binary Protection"
description: ""
category: iOS Security
tags: [iOS CodeSignature]
---
{% include JB/setup %}

### Get code signature

	codesign -l Clover
	Executable=/Users/gavingu/Desktop/Clover
	Identifier=com.tencent.clover
	Format=Mach-O thin (armv7)
	CodeDirectory v=20200 size=32782 flags=0x0(none) hashes=1630+5 location=embedded
	Hash type=sha1 size=20
	CDHash=bf502aa97e8d9bda3cd96d0cc4310afbeea1c157
	Signature size=3487
	Authority=Apple iPhone OS Application Signing
	Authority=Apple iPhone Certification Authority
	Authority=Apple Root CA
	Info.plist=not bound
	TeamIdentifier=9TV4ZYSS4J
	Sealed Resources=none
	Internal requirements count=1 size=100