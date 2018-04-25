# mariadb

Example:

``` yaml
    - role: mariadb
      users:
        - user: user1
          host: host1
        - user: user2
          host: host2
        - user: user3 # default host: localhost
      databases:
        - test_database
```