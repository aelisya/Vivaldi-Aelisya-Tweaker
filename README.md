# Aelisya Tweaker
![OSSAR](https://github.com/macqael/Aelisya-Tweaker/workflows/OSSAR/badge.svg)![CodeQL](https://github.com/macqael/Aelisya-Tweaker/workflows/CodeQL/badge.svg?branch=master)\
Add security and privacy with this extension.

- AMP Blocking.
- Blocking ping requests.
- Block CSP_REPORT.
- Block Sentry and Bugsnag.

## Installation
<a href="https://microsoftedge.microsoft.com/addons/detail/aelisya/ackodolhpbogckmcjkfdcgifhigeghkg"><img src="https://raw.githubusercontent.com/macqael/Aelisya-Tweaker/bd4575c1165645c7216b49e22a0b470c38efebfc/icons/EdgeStore.webp"></img></a>

## Report a bug or asking for a feature ?
Follow the template or the issue will be closed immediately without reading !

## Security Updates
- [NEW] For best Security the Microsoft Account who push the extension on edge store is now a passwordless-only account.

## Whats the commit "Verification commit" ?
See my [Security](https://github.com/BirdInFire/Aelisya-Tweaker/blob/master/SECURITY.md) to know more about that.

## Manifest V3
V7 added migration to Manifest V3.

## Release Notes

### V 7.1
<ul>
<li>Changing my username</li>
<li>Modification to url to match username</li>
<li>Change done to add more sucurity durint the update/developement on my side this update change noting to the extension</li>
</ul>

### V 7.0
<ul>
<li>Migration to Manifest V3</li>
<li>Removal of Scrollbar modification</li>
<li>Switch from redirect to complete block of AMP</li>
<li>Removal of ETAG blocker since it negativly affect the browsing experiences</li>
<li>The extension does not have to read the page anymore so permission are also removed for a better security</li>
</ul>

### V 6.4
<ul>
<li>Add css theme by css injection to remove blink on the scrollbar on slower computer</li>
</ul>

### V 6.3
<ul>
<li>Replace css theme injection by js injection at the end of the load to override enventual override of the scrollbar</li>
</ul>

### V 6.2
<ul>
<li>Removing noopener since edge do it automatically</li>
<li>Removing updgrade insecure request since edge do it automatically</li>
<li>Removing block of flash objet since flash insn't present anymore on W10 and edge</li>
</ul>

### V 6.1
<ul>
<li>Was a testing version who is now removed from the store</li>
</ul>

### V 6.0
<ul>
<li>Some tweak and removing option</li>
<li>Bug correction</li>
<li>light version for AdGuard Windows with userscript to compensate the script removed from light version for a better privacy/security</li>
<li>the light version don't iclude js or redirection so they don't ask for any permission at all</li>
</ul>

### V 5.0
<ul>
<li>Bug correction in AMP on unsecure http</li>
<li>Bug correction in noopener on unsecure http</li>
<li>Bug correction in scrollbar on unsecure http</li>
<li>E-tag tracking protection with DeclarativeNetRequest (preparation for manifest V3)</li>
<li>Removing nofollow addition in _blank link</li>
<li>Minor performance optimization</li>
<li>Adding option page (empty for now)</li>
<li>Design change of the popup page</li>
<li>Privacy policy moved on the store page for a better transparency</li>
</ul>

### V 4.0
<ul>
<li>Block CSP report with DeclarativeNetRequest (preparation for manifest V3)</li>
<li>Block sentry & bugsnag with DeclarativeNetRequest (preparation for manifest V3)</li>
<li>Block Flash object with DeclarativeNetRequest & remove with css(preparation for manifest V3)</li>
<li>Bug correction who doesn't redirect AMP page from another TLD than .com</li>
<li>Bug correction in AMP regexp</li>
</ul>

### V 3.0
<ul>
<li>Blocking ping requests with declarativeNetRequest (Preparation for Manifest V3)</li>
<li>Upgrade insecure (http) request with declarativeNetRequest for defeat mixed contents (Preparation for Manifest V3)</li>
<li>Add link to report bug or asking for news features</li>
<li>Change permission to all https (if you want to upgrade http to https on an https page we have to have right to do so)</li>
</ul>

### V 2.1
<ul>
<li>Rewriting AMP redirection from scratch with declarativeNetRequest instead of webrequest (Preparation for Manifest V3)</li>
<li>Rewriting CSP for more security (Preparation for Manifest V3)</li>
<li>Removing redirector background script (for AMP redirect) replaced by declarativeNetRequest</li>
<li>Protect the page in case of error of the extension</li>
<li>Reintegration of previously removed integrity-check for the popup</li>
<li>Adding support for color change who follow browser/os preference to scrollbar</li>
<li>Various optimizations for some js and manifest to try to improve speed and security</li>
<li>Adapting Scrollbar to edge system's settings one</li>
</ul>
