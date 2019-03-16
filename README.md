### docker-nginx-https

Test container with nginx & HTTPS. Generate a self-signed cert with private key and put into `ssl/`. Disclaimer - this is a test, not an example implementation.

1) Redirects `http` to `https` and sends HSTS header
2) Canonicalizes by removing `www` and sends HSTS header again