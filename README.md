# custom-mappings
This is my custom mapping file for use with [this script](https://github.com/RickDB/PlexAniSync).

I map everything that I have on my server to this script just so things work in the future. It also helps with multi season shows and the script not working well with those in the past.

If you want to set this up for yourself then add the following to your cron job to update it at midnight

``` bash
0 0 * * * curl -sL https://raw.githubusercontent.com/46620/custom-mappings/main/custom_mappings.yaml > /opt/Tautulli/scripts/PlexAniSync/custom_mappings.yaml
```
