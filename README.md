# List of Raspberry Pi Disk Images
**URL: https://raw.github.com/alexchamberlain/raspberrypi_images/master/list**

## Aim
To produce a machine readable list of Raspberry Pi images, for the purpose of writing a command line image downloader.

## Usage
The `list` file is designed to be used directly by software. Developers should take a look at it; the format is pretty obvious.

The software SHOULD:
1. Only download the `list` file over a secure connection, and verify the certificates in use.
2. Download the image by concatinating a mirror with a url.
3. Verify the download using the `sha1` hash.

## TODO
1. Provide examples of usage.
