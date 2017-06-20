### `certbot`

Note:

Certbot is a command line tool from the EFF that allows the creation of certificates in an automated fashion.

We use it to generate certificates for all of our sandbox environments. With a combination of rake tasks and certbot to create certificates every time we create a new sandbox. Once generated, they can be renewed by a single command (`certbot renew`).

https://certbot.eff.org/
