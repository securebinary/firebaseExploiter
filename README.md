<h4 align="center">Insecure Firebase CLI Scanner & Exploit.</h4>


<p align="center">
<a href="https://github.com/securebinary/firebaseExploiter/"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat"></a>
<a href="https://twitter.com/thesecurebinary"><img src="https://img.shields.io/twitter/follow/thesecurebinary.svg?logo=twitter"></a>
</p>
      
<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Install</a> •
  <a href="#running-firebaseexploiter">Usage</a>
</p>

## Features

![fileExploit](static/fileExploit.png)

 - Mass vulnerability scanning from list of hosts
 - Custom JSON data in `exploit.json` to upload during exploit
 - Custom `URI path` for exploit


## Usage

![Usage](static/usage.png)

This will display help for the CLI tool. Here are all the required arguments it supports.


## Installation

FirebaseExploiter was built using go1.19. Make sure you use latest version of [Go](https://go.dev/doc/install) to install successfully. Run the following command to install the latest version:

```bash
go install -v github.com/securebinary/firebaseExploiter@latest
```

![Install](static/install.png)

## Running FirebaseExploiter

To scan a specific domain to check for Insecure Firebase DB.

![urlVuln](static/urlVuln1.png)

![urlVuln](static/urlVuln2.png)

To exploit a Firebase DB to write your own JSON document in it.

![urlExploit](static/urlExploit.png)

Create your own `exploit.json` file in proper JSON format to exploit vulnerable Firebase DBs.

Checking the exploited URL to verify the vulnerability.

![urlResponse](static/urlResponse.png)

Adding `custom path` for exploiting Firebase DBs.

![urlPath](static/urlPath.png)

Mass scanning for Insecure Firebase Databases from list of target hosts.

![fileVuln](static/fileVuln.png)

Exploiting vulnerable Firebase DBs from the list of target hosts.

![fileExploit](static/fileExploit.png)

## License
`FirebaseExploiter` is made with 🖤 by the `SecureBinary` team. Any tweaks / community contribution are welcome.
