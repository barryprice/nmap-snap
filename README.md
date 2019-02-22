<h1 align="center">
  <a href="https://nmap.org/">
    <img src="https://nmap.org/images/nmap-logo-256x256.png" alt="nmap">
    <br />
    Nmap snap
  </a>
</h1>

<p align="center">
  <b>This is the snap for <a href="https://nmap.org/download.html"><code>nmap</code></a></b>.
  <br/>
  Nmap ("Network Mapper") is a free and open source (license) utility for network discovery and security auditing.
  <br/>
  It works on Ubuntu, Fedora, Debian, and other major Linux distributions.
</p>

<p align="center">
  <a href="https://snapcraft.io/nmap"><img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" /></a>
</p>


## Command-line Installation

    sudo snap install nmap

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

That'll install the latest _stable_ release of `nmap`.

Or, if you're feeling adventurous, try the in-progress _next release_ from the `edge` channel:

    sudo snap install nmap --edge

## Permissions

Once installed, this snap needs manually connecting to some plugs:

    sudo snap connect nmap:network-control


## The Snapcrafters

[maxiberta](https://github.com/maxiberta/)

## Upstream

[Nmap](https://nmap.org/)