## Proxy reverso com NGINX

- Definir os hosts locais para aplicações

```bash
sudo nano /etc/hosts
```

```
127.0.0.1       host.docker.internal
```

Obs: No windows podemos adicionar o dns host.docker.internal, conforme https://gist.github.com/zenorocha/18b10a14b2deb214dc4ce43a2d2e2992

- Rodar aplicações

```bash
docker-compose up -d
```

- Abrir aplicação no navegador

```
http://localhost
```
