# AddStore
Updated Windows Store installation for LTSC

Recently I've noticed that this one: https://github.com/kkkgo/LTSC-Add-MicrosoftStore stops working. It installs but it is not updating itself due to some weird manifests errors. I've just updated the packages and patched the script a bit, so now it works.

Just unpack "package.7z" and run "Add-Store.cmd" with elevated admin rights. "Add-Store-Original.cmd" is just the original file taken from https://github.com/kkkgo/LTSC-Add-MicrosoftStore
