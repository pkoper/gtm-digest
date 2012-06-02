# GT.M Digest Extension

This simple OpenSSL based digest extension is a simple M interface to MD5, SHA1, SHA2 and other OpenSSL message digest implementations.


<pre>
GTM>w $$sha^digest("Hello"),!
d7f56f62cde2a044d0259adf01953bbb8f971a33

GTM>w $$sha224^digest("Hello"),!
4149da18aa8bfc2b1e382c6c26556d01a92c261b6436dad5e3be3fcc

GTM>w $$sha256^digest("Hello"),!
185f8db32271fe25f561a6fc938b2e264306ec304eda518007d1764826381969

GTM>w $$sha512^digest("Hello"),!
3615f80c9d293ed7402687f94b22d58e529b8cc7916f8fac7fddf7fbd5af4cf777d3d795a7a00a16bf7e7f3fb9561ee9baae480da9fe7a18769e71886b03f315

GTM>w $$md5^digest("Hello"),!
8b1a9953c4611296a827abf8c47804d7

GTM>zsy "echo -n Hello | md5sum"
8b1a9953c4611296a827abf8c47804d7  -

GTM>
</pre>
