Chef Repository for OpenStack
===========================

Prerequisites
-------------

1. Install gem packages

```
gem install knife-solo knife-solo_data_bag berkshelf
```

Data Bag
--------

1. Create Data Bag Key

```
openssl rand -base64 512 | tr -d '\r\n' > data_bag_key
```

