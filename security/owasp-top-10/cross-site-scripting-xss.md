---
description: A7 - CROSS-SITE SCRIPTING
---

# Cross Site Scripting \(XSS\)

## What it is

A common form of online Web-Attacks.  
As the name implies, it allows an attacker  
to execute a script on a regular website if inputs aren’t sanitized

## Dangers and impact

* Steal authentication cookies
* Inject HTMl to steal information
* CSRF
* Bypass authentication methods

## Prevent XSS

* Escape Inputs \(Example: &lt; → &lt\)
* Validate Inputs \(Comparing\)
* Sanitize \(Combination\)
* Don’t use untrusted data unless correctly escaped

{% embed url="https://snyk.io/blog/xss-attacks-the-next-wave/" %}

{% embed url="https://xss-game.appspot.com" %}





