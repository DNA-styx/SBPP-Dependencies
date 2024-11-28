![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/DNA-styx/SBPP-Dependencies/total)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/DNA-styx/SBPP-Dependencies)


# SBPP-Dependency

A automated archive of all dependences required to install SourceBann++. For use with web hosts that don't allow/support SSH access<br>

## Getting Started

Download the latest version from the Releases page. Upload the 'includes' folder to your SourceBans++ site, overwriting any fiels already in there.

### Prerequisites

* Web host that supports PHP 8.2
* FTP/CPanel access to your web server to upload files
* All other SourceBans++ prerequisites

### Installation
New Install of SourceBanns++

1. Download the latest release of SourceBans++ from <a href="https://github.com/sbpp/sourcebans-pp/releases">here</a>
2. Download the latest release of SBPP Dependencies from <a href="https://github.com/DNA-styx/SBPP-Dependency-Downloader/releases">here</a>
3. Upload the contents of the ``web`` folder from SourceBans++ archive to your web server
4. Upload the ``includes`` folder from SBPP Dependencies archive to your web server
5. Go to ``your web site address``/install/ in your web browser to start the install

## Troubleshooting

### `Compose autoload not found! Run composer install in the root directory of your SourceBans++ installation.`
FTP to your web host, browse to the ``includes`` folder and ensure there is a ``vendor`` folder inside it. <br>
![image](https://github.com/user-attachments/assets/a70c8515-2eb5-4d3d-8099-e93f3dc18d1a)

Open the vendor folder and ensure there are files in it. They should look like the below.
![image](https://github.com/user-attachments/assets/e3448a76-e98d-4680-8917-4b9b65363288)


## Additional Documentation and Acknowledgments

* Based on https://gist.github.com/okwasniewski/f7fd39e1f65b3d2cc1de7f39eef58d55 
* With tweaks from: https://stackoverflow.com/a/71716411 & https://stackoverflow.com/a/75250838
