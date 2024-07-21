Automated RPM build for awscliv2 https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Builds are available in the Releases section.

Or install the package from a `rpm` repository:

For `RHEL 8/9` based OS (CentOS, Amazon Linux, Oracle Linux, Rocky Linux, AlmaLinux, etc.):

```bash
echo -e "[awscliv2]
name=awscliv2 repo on packages.bespin.ovh
comment=awscliv2 repo on packages.bespin.ovh
baseurl=https://packages.bespin.ovh/repo/awscliv2_prod
enabled=1
gpgkey=https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub
gpgcheck=1" > /etc/yum.repos.d/awscliv2.repo
```