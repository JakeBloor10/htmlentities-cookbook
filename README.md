Publishing to Opscode Community
-------------------------------

First, bump the version number in metadata.rb.

Then, run a knife script to generate the `metadata.json` file from `metadata.rb`.

```
knife cookbook metadata .
```

Then, making sure that the repo folder is called `htmlentities`, zip the folder and upload as `.tar` file to Opscode Community.

```
tar -czf htmlentities.tar.gz htmlentities
```
