docker-wpscan
=============

Pull the repo with ```sudo docker pull wpscanteam/wpscan```

Start WPScan either directly
```sudo docker run wpscanteam/wpscan wpscan -u http://yourblog.com [options]```

or in the container: 
```sudo docker -t -i run wpscanteam/wpscan bash```
```# wpscan -u http://yourblog.com [options]```

For the available Options, please see https://github.com/wpscanteam/wpscan#wpscan-arguments
