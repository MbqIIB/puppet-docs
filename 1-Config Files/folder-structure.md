Folder Structure
================


**puppet open source with environments**

```
/etc/puppet
├── auth.conf
├── environments
│   ├── default
│   │   ├── manifests
│   │   │   └── site.pp
│   │   └── modules
│   │       └── motd
│   │           └── manifests
│   │               └── init.pp
│   ├── dev
│   │   ├── manifests
│   │   │   └── site.pp
│   │   └── modules
│   │       ├── base
│   │       │   └── manifests
│   │       │       ├── init.pp
│   ├── prd
│   │   └── manifests
│   │       └── site.pp
│   ├── production
│   │   ├── manifests
│   │   │   └── site.pp
│   │   └── modules
│   │       └── motd
│   │           └── manifests
│   │               └── init.pp
│   └── uat
│       ├── manifests
│       │   └── site.pp
│       └── modules
│           ├── base
│           │   └── manifests
│           │       ├── init.pp
├── fileserver.conf
├── hieradata
│   └── sshkeys.yaml
├── hiera.yaml
├── manifests
│   └── site.pp
├── modules
├── puppet.conf
└── README.md
```


**puppet enterprise**

```
/etc/puppetlabs/puppet
.
├── auth.conf
├── console.conf
├── files
├── fileserver.conf
├── hieradata
│   ├── common.yaml
│   ├── dev.yaml
│   ├── prd.yaml
├── hiera.yaml
├── manifests
│   └── site.pp
├── modules
│   ├── apache
│   │   ├── files
│   │   ├── manifests
│   │   │   ├── init.pp
│   │   │   ├── package.pp
│   │   │   ├── params.pp
│   │   │   ├── service.pp
│   │   │   └── vhost.pp
│   │   ├── templates
│   │   │   ├── index.html.erb
│   │   │   └── vhost.conf.erb
│   │   └── tests
│   │       └── init.pp
├── puppet.conf
├── puppetdb.conf
├── routes.yaml
└── ssl
    ├── ca
    │   ├── ca_crl.pem
    │   ├── ca_crt.pem
    │   ├── ca_key.pem
    │   ├── ca_pub.pem
    │   ├── inventory.txt
    │   ├── private
    │   │   └── ca.pass
    │   ├── requests
    │   ├── serial
    │   └── signed
    │       ├── pe-internal-broker.pem
    │       ├── pe-internal-dashboard.pem
    │       ├── pe-internal-mcollective-servers.pem
    │       ├── pe-internal-peadmin-mcollective-client.pem
    │       ├── pe-internal-puppet-console-mcollective-client.pem
    │       ├── victorbrca1.mylabserver.com.pem
    │       ├── victorbrca2.mylabserver.com.pem
    │       └── victorbrca3.mylabserver.com.pem
    ├── certificate_requests
    ├── certs
    │   ├── ca.pem
    │   ├── pe-internal-broker.pem
    │   ├── pe-internal-mcollective-servers.pem
    │   ├── pe-internal-peadmin-mcollective-client.pem
    │   ├── pe-internal-puppet-console-mcollective-client.pem
    │   └── victorbrca1.mylabserver.com.pem
    ├── crl.pem
    ├── private
    ├── private_keys
    │   ├── pe-internal-broker.pem
    │   ├── pe-internal-mcollective-servers.pem
    │   ├── pe-internal-peadmin-mcollective-client.pem
    │   ├── pe-internal-puppet-console-mcollective-client.pem
    │   └── victorbrca1.mylabserver.com.pem
    └── public_keys
        ├── pe-internal-broker.pem
        ├── pe-internal-mcollective-servers.pem
        ├── pe-internal-peadmin-mcollective-client.pem
        ├── pe-internal-puppet-console-mcollective-client.pem
        └── victorbrca1.mylabserver.com

```
