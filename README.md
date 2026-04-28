# Roastduck Blog

Static personal homepage for `roastduck.xyz`.

## Content

- Travel notes
- Study notes
- GitHub project links
- Personal timeline

## Deploy

Copy the files to the server web root:

```bash
sudo rsync -av ./ /var/www/site/
sudo nginx -t
sudo systemctl reload nginx
```

Current production server:

```text
43.161.250.225:/var/www/site
```
