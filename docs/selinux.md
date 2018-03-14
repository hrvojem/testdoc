# SELinux testing - permissive

Testing SE Linux when set on permissive

## Testing **Percona Server**

* Standard clean PS 5.6 installation works correctly

### Testing **TokuBackup**

This requires variable `innodb_use_native_aio` set to `0`.

