# SLAB injection technique
Inject pages to Linux SLAB caches, which might be really useful when dealing with embedded devices having to allocate a lot of objects in atomic context.

Use this to inject pages to a cache:
```
make
sudo ./inject_page.sh cachename [number of pages]
```

To check existing caches:
```
sudo cat /proc/slabinfo
```
