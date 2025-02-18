<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/deploy/writable.php -->
<!-- Then run bin/docgen -->

# writable

[Source](/recipe/deploy/writable.php)




## Configuration
### http_user
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L9)





### http_group
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L26)

Used to make a writable directory by a server.
Used in `chgrp` mode of [writable_mode](/docs/recipe/deploy/writable.md#writable_mode) only.
Attempts automatically to detect http user in process list.



### writable_dirs
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L41)

List of writable dirs.



### writable_mode
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L48)

One of:
- chown
- chgrp
- chmod
- acl

```php title="Default value"
'chgrp'
```


### writable_use_sudo
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L51)

Using sudo in writable commands?

```php title="Default value"
false
```


### writable_recursive
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L54)

Use recursive mode (-R)?

```php title="Default value"
false
```


### writable_chmod_mode
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L57)

The chmod mode.

```php title="Default value"
'0755'
```



## Tasks

### deploy:writable
[Source](https://github.com/deployphp/deployer/blob/master/recipe/deploy/writable.php#L60)

Make writable dirs.




