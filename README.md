# Ansible Modules for Dell Technologies Unity

The Ansible Modules for Dell Technologies (Dell) Unity allow Data Center and IT administrators to use RedHat Ansible to automate and orchestrate the configuration and management of Dell Unity arrays.

The capabilities of the Ansible modules are managing consistency groups, filesystem, filesystem snapshots, CIFS server, NAS server, NFS server, NFS export, SMB share, interface, hosts, snapshots, snapshot schedules, storage pools, user quotas, quota trees and volumes. Capabilities also include gathering facts from the array. The options available for each are list, show, create, modify and delete. These tasks can be executed by running simple playbooks written in yaml syntax. The modules are written so that all the operations are idempotent, so making multiple identical requests has the same effect as making a single request.

## Table of contents

* [Code of conduct](https://github.com/dell/ansible-unity/blob/1.5.0/docs/CODE_OF_CONDUCT.md)
* [Maintainer guide](https://github.com/dell/ansible-unity/blob/1.5.0/docs/MAINTAINER_GUIDE.md)
* [Committer guide](https://github.com/dell/ansible-unity/blob/1.5.0/docs/COMMITTER_GUIDE.md)
* [Contributing guide](https://github.com/dell/ansible-unity/blob/1.5.0/docs/CONTRIBUTING.md)
* [Branching strategy](https://github.com/dell/ansible-unity/blob/1.5.0/docs/BRANCHING.md)
* [List of adopters](https://github.com/dell/ansible-unity/blob/1.5.0/docs/ADOPTERS.md)
* [Maintainers](https://github.com/dell/ansible-unity/blob/1.5.0/docs/MAINTAINERS.md)
* [Support](https://github.com/dell/ansible-unity/blob/1.5.0/docs/SUPPORT.md)
* [License](#license)
* [Security](https://github.com/dell/ansible-unity/blob/1.5.0/docs/SECURITY.md)
* [Prerequisites](#prerequisites)
* [List of Ansible modules for Dell Unity](#list-of-ansible-modules-for-dell-unity)
* [Installation and execution of Ansible modules for Dell Unity](#installation-and-execution-of-ansible-modules-for-dell-unity)
* [Releasing, Maintenance and Deprecation](#releasing-maintenance-and-deprecation)

## License
The Ansible collection for Unity is released and licensed under the GPL-3.0 license. See [LICENSE](https://github.com/dell/ansible-unity/blob/1.5.0/LICENSE) for the full terms. Ansible modules and module utilities that are part of the Ansible collection for Unity are released and licensed under the Apache 2.0 license. See [MODULE-LICENSE](https://github.com/dell/ansible-unity/blob/1.5.0/MODULE-LICENSE) for the full terms.

## Supported Platforms
  * Dell Unity Arrays version 5.1, 5.2

## Prerequisites
This table provides information about the software prerequisites for the Ansible Modules for Dell Unity.

| **Ansible Modules** | **Python version** | **Storops - Python SDK version** | **Ansible** |
|---------------------|--------------------|----------------------------------|-------------|
| v1.5.0 | 3.9 <br> 3.10 <br> 3.11 | 1.2.11 | 2.12 <br> 2.13 <br> 2.14|

## Idempotency
The modules are written in such a way that all requests are idempotent and hence fault-tolerant. It essentially means that the result of a successfully performed request is independent of the number of times it is executed.

## List of Ansible Modules for Dell Unity
  * [Consistency group module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#consistency-group-module)
  * [Filesystem module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#filesystem-module)
  * [Filesystem snapshot module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#filesystem-snapshot-module)
  * [Info module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#info-module)
  * [Host module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#host-module)
  * [CIFS server module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#cifs-server-module)
  * [NAS server module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#nas-server-module)
  * [NFS server module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#nfs-server-module)
  * [NFS export module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md##nfs-module)
  * [SMB share module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#smb-share-module)
  * [Interface module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#interface-module)
  * [Snapshot module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#snapshot-module)
  * [Snapshot schedule module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#snapshot-schedule-module)
  * [Storage pool module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#storage-pool-module)
  * [User quota module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#user-quota-module)
  * [Quota tree module ](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#quota-tree-module)
  * [Volume module](https://github.com/dell/ansible-unity/blob/1.5.0/docs/Product%20Guide.md#volume-module)

## Installation and execution of Ansible modules for Dell Unity

The installation and execution steps of Ansible modules for Dell Unity can be found [here](https://github.com/dell/ansible-unity/blob/1.5.0/docs/INSTALLATION.md).

## Releasing, Maintenance and Deprecation

Ansible Modules for Dell Technnologies Unity follows [Semantic Versioning](https://semver.org/).

New version will be release regularly if significant changes (bug fix or new feature) are made in the collection.

Released code versions are located on "release" branches with names of the form "release-x.y.z" where x.y.z corresponds to the version number. More information on branching strategy followed can be found [here](https://github.com/dell/ansible-unity/blob/1.5.0/docs/BRANCHING.md).

Ansible Modules for Dell Technologies Unity deprecation cycle is aligned with that of [Ansible](https://docs.ansible.com/ansible/latest/dev_guide/module_lifecycle.html).
