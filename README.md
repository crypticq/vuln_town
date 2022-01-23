# VulnTown

Vulnrable docker container for deployment

## Deployment of DVWA

To deploy DVWA run

```bash
  docker pull vulnerables/web-dvwa
  docker run --rm -it -p 80:80 vulnerables/web-dvwa

```


## Deployment of juiceshoop

To deploy OWASP juice shop run

```bash
  docker pull bkimminich/juice-shop
  docker run --rm -it -p 3000:1337 bkimminich/juice-shop

```

## Deployment of mutillidae

To deploy OWASP mutillidae run

```bash
    docker pull szsecurity/mutillidae
    docker run -p 1337:80 szsecurity/mutillidae

```        
