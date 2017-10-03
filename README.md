# ecbyo vagrant

1. Clone this repo
2. Clone this repo https://github.com/ivacationonline/ecbyo alongside of Vagrantfile
3. Place db backup alongside of Vagrantfile. The name of the dump file must be `ecbyo_sc.bak`
4. `vagrant up` (hostmanager may ask you the root password for adding ecbyo.local to /etc/hosts)
5. Go to http://ecbyo.local/add-rank . Current dump doesn't contain required data from property_rank table. 
  This action will add dummy data for proper work.
6. The website is running on http://ecbyo.local/
