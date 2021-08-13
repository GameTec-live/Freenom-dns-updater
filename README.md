# Freenom dns updater
[![GitHub license](https://img.shields.io/github/license/maxisoft/Freenom-dns-updater)](https://github.com/maxisoft/Freenom-dns-updater/blob/main/LICENSE.txt)
![Unit Test dev and main branch](https://github.com/maxisoft/Freenom-dns-updater/workflows/Unit%20Test%20dev%20and%20main%20branch/badge.svg)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/Freenom-dns-updater)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/maxisoft/Freenom-dns-updater.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/maxisoft/Freenom-dns-updater/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/maxisoft/Freenom-dns-updater.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/maxisoft/Freenom-dns-updater/context:python)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=maxisoft_Freenom-dns-updater&metric=alert_status)](https://sonarcloud.io/dashboard?id=maxisoft_Freenom-dns-updater)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=maxisoft_Freenom-dns-updater&metric=ncloc)](https://sonarcloud.io/dashboard?id=maxisoft_Freenom-dns-updater)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=maxisoft_Freenom-dns-updater&metric=vulnerabilities)](https://sonarcloud.io/dashboard?id=maxisoft_Freenom-dns-updater)
[![deepcode](https://www.deepcode.ai/api/gh/badge?key=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJwbGF0Zm9ybTEiOiJnaCIsIm93bmVyMSI6Im1heGlzb2Z0IiwicmVwbzEiOiJGcmVlbm9tLWRucy11cGRhdGVyIiwiaW5jbHVkZUxpbnQiOmZhbHNlLCJhdXRob3JJZCI6MjIxNjYsImlhdCI6MTU5ODc5ODUyNn0.S6xv8IeJvEm6gE7HYJe4wHdv2hIX0tYFvGAZIonb9ac)](https://www.deepcode.ai/app/gh/maxisoft/Freenom-dns-updater/_/dashboard?utm_content=gh%2Fmaxisoft%2FFreenom-dns-updater)

###Note from Froker:
The update portion didnt work, so i forked it and here you go.Have fun!

A tool written in python to update [freenom](http://Freenom.com)

### Main Features
* Manage (add/update/remove) a domain's dns record with cli
* Auto renew domains (thanks to [Cedric Farinazzo](https://github.com/cedricfarinazzo))
### Installation
```bash
python3 setup.py install
```
### Examples
```bash
#!/bin/bash
IP=$(curl https://checkip.amazonaws.com)
fdu domain forward -u http://$IP/ email passwd eample.tk
fdu domain renew email passwd example.tk
```
