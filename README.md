# puppyblocker

This is a GitHub Pages project to redirect http://mac.puppyhoff.me to here.

By adding the following lines to your `/etc/hosts` file, you can prevent somebody from running the puppyhoff script on your mac:

```
192.30.252.153	mac.puppyhoff.me
192.30.252.154	mac.puppyhoff.me
```

This points `mac.puppyhoff.me` to GitHub's IP address, which then points to this project.
