# Add municipalities of South Tyrol in Kibanas Region Map visualizations

1) Upload [municipalities.json](https://github.com/puecher/kibana-municipalities-south-tyrol/blob/master/municipalities.json) to your hosting account (special thanks to [Geoportal South Tyrol](http://geoportal.buergernetz.bz.it/) for the vector layers using the GeoServers Web Feature Service (https://geoservices.buergernetz.bz.it/geoserver/ows?service=WFS&version=2.0.0&request=GetFeature&typeName=p_bz-administrative_units:Municipalities&outputFormat=application/json&maxFeatures=200&SrsName=EPSG:4326))
2) Enable cross-origin resource sharing (for Apache see [.htaccess](https://github.com/puecher/kibana-municipalities-south-tyrol/blob/master/.htaccess))
3) Add regionmap settings to your kibana.yml file (see [kibana.yml](https://github.com/puecher/kibana-municipalities-south-tyrol/blob/master/kibana.yml)).
4) Have fun with it! •ᴗ•
