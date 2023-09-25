# Vagrant WordPress Development Environment

This Vagrant configuration sets up a development environment for WordPress using Ubuntu.

## Prerequisites

Before using this Vagrant setup, ensure you have the following software installed on your system:

- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)

## Getting Started

1. **Clone this repository to your local machine.**
2. **Navigate to the project directory**
3. **Start the virtual machine: *vagrant up***
4. **Access the WordPress site in your web browser at http://192.168.56.30.**

# Configuration
    Guest OS: Ubuntu
    Private Network IP: 192.168.56.30
    Public Network Enabled
    VirtualBox Memory: 2048 MB

# Provisioning
The Vagrant box is provisioned with the following software packages and configurations:

    Apache HTTP Server
    Ghostscript
    PHP with various extensions
    MySQL Server
    WordPress (latest version)
    Apache Virtual Host for WordPress

# WordPress Database Credentials

    Database Name: wordpress
    Database User: wordpress
    Database Password: admin123

Customizing the Configuration

You can customize the Vagrant configuration and provisioning settings in the Vagrantfile to match your requirements.
