**bettercap** is a complete, modular, portable and easily extensible **MITM** tool and framework with every kind of diagnostic
and offensive feature you could need in order to perform a man in the middle attack.

<table>
    <tr>
        <th>Version</th>
        <td>
          <a href="https://badge.fury.io/rb/bettercap" target="_blank">
            <img src="https://badge.fury.io/rb/bettercap.svg"/>
          </a>
        </td>
    </tr>
    <tr>
        <th>Homepage</th>
        <td><a href="https://www.bettercap.org/">https://www.bettercap.org/</a></td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td><a href="https://github.com/evilsocket/bettercap">https://github.com/evilsocket/bettercap</a></td>
     <tr/>
    <tr>
        <th>Code Documentation</th>
        <td>
          <a href="http://www.rubydoc.info/github/evilsocket/bettercap">http://www.rubydoc.info/github/evilsocket/bettercap</a>
          &nbsp;
          <a href="https://codeclimate.com/github/evilsocket/bettercap" target="_blank">
            <img src="https://codeclimate.com/github/evilsocket/bettercap/badges/gpa.svg"/>
          </a>
        </td>
    </tr>
    <tr>
       <th>Author</th>
       <td><a href="https://www.evilsocket.net/">Simone Margaritelli</a> (<a href="https://twitter.com/evilsocket">@evilsocket</a>)</td>
    </tr>
    <tr>
        <th>Twitter</th>
        <td><a href="https://twitter.com/bettercap">@bettercap</a></td>
    </tr>
    <tr>
        <th>Copyleft</th>
        <td>Simone Margaritelli</td>
    </tr>
    <tr>
        <th>License</th>
        <td>GPL v3.0 - (see LICENSE file)</td>
    </tr>
</table>

Installation
============

**Dependencies**

All dependencies will be automatically installed through the RubyGems system but in some cases you might need to install some system
dependency in order to make everything work.

**On OSX** (install brew and xcode tools first):

```shell
brew install libpcap
```

**On Linux**:

```shell
sudo apt-get install build-essential ruby-dev libpcap-dev net-tools
```

This should solve issues such as [this one](https://github.com/evilsocket/bettercap/issues/22) or [this one](https://github.com/evilsocket/bettercap/issues/100).

**Stable Release (RubyGems)**

```shell
gem install bettercap
```

**From Source**

```shell
git clone https://github.com/evilsocket/bettercap
cd bettercap
gem build bettercap.gemspec
sudo gem install bettercap*.gem
```

**Installation on Kali Linux**

Kali Linux has bettercap packaged and added to the **kali-rolling** repositories. To install bettercap and all dependencies in one fell swoop on the latest version of Kali Linux:
   
```shell
apt-get update
apt-get dist-upgrade
apt-get install bettercap
```

**Installation on Parrot Security OS**

Parrot Security has bettercap packaged and added to the **ParrotSec** repositories. To install bettercap and all dependencies in one fell swoop on the latest version of Parrot Security:
   
```shell
apt-get update
apt-get dist-upgrade
apt-get install bettercap
```

Documentation and Examples
============

Please refer to the [official website](https://www.bettercap.org/).
