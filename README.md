# forward-proxy-httpd24-win

## Overview
'forward-proxy-httpd24-win' is example of forward proxy configuration using Apache HTTP Server 2.4 running in Windows.

## Installation
1. Download and install Apache HTTP Server 2.4 Windows binary (https://httpd.apache.org/download.cgi).
1. Start command prompt in administrator mode.
1. Run initial starting Apache.
    ```sh
    cd <Apache install folder>
    httpd -k install
    httpd -k start
    ```
1. Clone this repository.
    ```sh
    git clone https://github.com/backroot/forward-proxy-httpd24-win.git
    ```

## Configuration
1. Copy the `conf` folder to the folder where Apache is installed.
1. Restart the Apache server.
    ```sh
    httpd -k restart
    ```

## How to use
Configure proxy settings in your browser or other client and specify `http://your-windows:3128` as the proxy server.
If you can't connect, check your Windows Firewall settings.

## License
This project is released under the [MIT LICENSE].

## Contribution
Contributions are welcome. Please raise an issue before submitting a pull request.

## Author
- [backroot](https://github.com/backroot)
