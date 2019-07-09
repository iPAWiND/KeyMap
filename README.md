# KeyMap
Map keyboard clicks to touch events

[Demo](https://twitter.com/iPAWiND/status/1145435103662923782)

## Getting Started

### Non-Jailbroken

Mac is required

Create dylibs folder and download the dynamic library

    mkdir ~/Desktop/dylibs && cd ~/Desktop/dylibs && curl -LO https://github.com/iPAWiND/KeyMap/releases/download/dynamic-library/latest.zip && unzip latest.zip && rm latest.zip

#### Patching

Using [iPatch](https://github.com/iPAWiND/iPatch)

    cd ~/Desktop/iPatch && ./ipatch.sh 'path_to_ipa_file' ~/Desktop/dylibs 'path_to_mobile_provision(optional)'

### Jailbroken

Add source

    https://apt.ipawind.com

## Acknowledgments

* This project is distributed publicly in hope that it will be useful for many people
* This project comes as is, without any warranty or guarantee
