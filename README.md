ip address: 52.35.176.86
ssh port:
host: http://ec2-52-35-176-86.us-west-2.compute.amazonaws.com

URL: http://52.35.176.86

Softwares Installed:
upgraded all the softwares present
apache2
postgresql
libapache2-mod-wsgi
python pip
git
virtualenv for python

Configurations made:
1. Configured sudoers.d to give grader sudo access
2. Configured timezone to UTC
3. Configured sshd_config for ssh port
4. Configured ufw for firewalls
5. Configured apache2 
6. Configured  /etc/postgresql/9.3/main/pg_hba.conf to make sure postgres does not allow remote connections
7. changed /var/www folder permissions to give apache write permissions on DB and the images folder
8. Configured google secret json file to reflect right origin and callback URL
9. Created catalog.wsgi file


udacity_key.rsa
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEAvKWCt+TU25iMOmkTFRvsTlJuPtc1aNg8nn5nxwdKeiMa0ZMO
V4nM4SRv7jifLu0Amvu4g0xDkZhwp45ytD7kbBWFIXCd+oKuR6qAS6wFZTjGXzhd
7NF6bpchoEyjy0fsfRxOxwlt4CrNzcTNG7kNaAbhhE4dqljE92tLIwRDE3VcgZnN
tLFooFyyycGCYfW1N9frxA+mATM6LiEzC7iWHyyYQked8Tys4pMJZ5sCKRJlI/g/
FWo9mPy2pgiOlsWgjOAtjw/lP5ADbndSq/R+TdCiPDsp4YAdHd6j8yW9VIFFP2Xb
Lr8sqPLgvDAqd6RyxpVfPfDoImOLJMOVGcvp0wIDAQABAoIBABLzrcY7vwawtKXJ
mJkuTPcxYNH/XOZDkxN5L4PXP6w1iqQzWeWBeovD1VrhZVyZgs4PK+JE7yTZY7fx
n6RsDRausslBPx3Dsy6P+oOfrIsWwRcf2o/IG7ywgjhQesQZXbDT/zYPxHIY2sQp
WVHHrYkd59oa3vAWKvOQW+QQsYxquYM9eraZJBvs8bkoZF5slEoRUwDHen6CFSWB
iVj1hFPqls8eGyWQIZVwXCRT15YuJKZ2fcbGO3dHV5Mtdozb62ZRK933PHI4XXWb
hzsOazo5GC+/QatSV9f0v4KlE3tMXO123XEC93cWZXA1o6pD+ofyqIpM5py63aIw
wD7vcgECgYEA9wVWOOgj1hbl8eSvBS0coUGTBWkFikMwCtlcqnK+EiiPOfU1WDf7
6YqFoAQ0zEzeaXxvJD747h5w2YMqQ20xUEn1+AQ0yaiZio7b42QWkOlkN51P6xJS
0ptYm6BMv7u7QUPpk5PNtjhqRI9h020JyMDQWG6mwBH/r2li63dMXOECgYEAw4D4
Eu3/UGVXHfmFDeTekk3E27KpPglr3njmy2C4rUc4etoZplHaxP5kcjoHfzDmG9NF
wG0mQjM0gFfc+3EGxcEGvdGoACj4+RuaUDrk1lleU0I+3VkhWQpG6J6RNZKO8x0+
RDA8GQrmrzQm1zNd0k6qkVkv/gIGI2O46HsBiTMCgYEA4sPocldRRqFAuH4J2cOf
C74J/KZ7qoChYuRFuEebi0nmqfsb3H+QZ8V9g/c4jPBoIQhVcz3IAbi6OkO6Ean0
4lLzVZpu5006nsMkwyvHt4I6OP/WNONeWu63Oi6/Jiht760riQnfh89kZsoFsTTh
DYVL/lKeC6a6RUqGv8iFtqECgYBwWAA2AIWikVmKZARNg6NSt1XUWcpfV9KguSEG
5cG58R9HmWT76jWo1faqnSYJtPPGMZX3icFecUZOKi9WXhDiOpXBJmVAEktf+rim
OfGeKyTE+2BcmgdLv1gX/Ga9Pkbe9YL+dClUyqrdKz7WkzHq1EG33GRztn4IgBmV
nnm3eQKBgQDoj++4Qq3m1xmdgnIYqPzexJk71y8LbLSi5+Px9AloXMVZ3kPJOxw6
aOx1dqw2mlzKFfsrLsOINYMH2M9BTnvX+Jlgarzs2fvFHTsK56ZWckoVqZJNGaN7
BNbM935WNuUUQq9uPHGnINx1f4uel+m5xfYQQgXR20MhMCN6ibHa9Q==
-----END RSA PRIVATE KEY-----
