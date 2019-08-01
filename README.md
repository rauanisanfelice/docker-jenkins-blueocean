![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rauanisanfelice/jenkins-blueocean.svg)
![GitHub top language](https://img.shields.io/github/languages/top/rauanisanfelice/jenkins-blueocean.svg)
![GitHub pull requests](https://img.shields.io/github/issues-pr/rauanisanfelice/jenkins-blueocean.svg)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/rauanisanfelice/jenkins-blueocean.svg)
![GitHub contributors](https://img.shields.io/github/contributors/rauanisanfelice/jenkins-blueocean.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/rauanisanfelice/jenkins-blueocean.svg)

![GitHub stars](https://img.shields.io/github/stars/rauanisanfelice/jenkins-blueocean.svg?style=social)
![GitHub followers](https://img.shields.io/github/followers/rauanisanfelice.svg?style=social)
![GitHub forks](https://img.shields.io/github/forks/rauanisanfelice/jenkins-blueocean.svg?style=social)

# Jenkins Blueocean

Template docker Jenkins

### Iniciando Docker
```console
docker-compose up -d
```

### Pegando chave do jenkins
```console
docker exec jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
```