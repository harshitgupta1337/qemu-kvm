===================
qemu-kvm development
===================

qemu-kvm is maintained in a `source tree`_ rather than directly in dist-git.
This provides way to develope using regular source code structure and provides 
way to generate SRPM and build using koji service. In addition, local build using
CentOS 9 Stream specific configuration.

Developers deliver all changes to source-git using merge request. Only maintainers
will be pushing changes sent to source-git to dist-git.

Each release in dist-git is tagged in the source repository so you can easily
check out the source tree for a build. The tags are in the format
name-version-release, but note release doesn't contain the dist tag since the
source can be built in different build roots (Fedora, CentOS, etc.)

.. _source tree: https://gitlab.com/redhat/centos-stream/src/qemu-kvm

