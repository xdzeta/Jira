# Laravel Socialite Jira OAuth1 Provider

## Documentation

provider for https://github.com/SocialiteProviders

A private-public key pair is required to establish OAuth authorisation with an Atlassian product. The private key and public key can be generated using openssl:

$ openssl genrsa -out rsa-key.pem 1024
$ openssl rsa -in rsa-key.pem -pubout -out rsa-key.pub
