# Vagrant Solr box

Box to get a Solr environment quickly up and running in a VM. If you plan to modify the Solr configuration copy the content of this repo to a new repo.

## Running the box

1. After cloning run:
`git submodule init`
`git submodule update`
2. Install [Vagrant](http://www.vagrantup.com/)
3. Run `vagrant up`
4. Open http://localhost:8983/solr/#/ (on host)


####Note
If you have problems with the startup job double check that scripts/etc/init/solr.conf has LF endings and not CRLF
