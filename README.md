# issue

****
fatal: Out of memory, malloc failed (tried to allocate 2000000000 bytes)
--
    :git config --global http.postBuffer 1024
    
****
curl: (56) GnuTLS recv error (-54): Error in the pull function.
--
    :git config --global http.postBuffer 2000000000
