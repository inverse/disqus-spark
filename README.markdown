# Disqus Spark

A simple way to incorporate [DISQUS][1] into your CodeIgniter application.

## Requirements

1. CodeIgniter
2. Sparks

## Documentation

First add your DISQUS shortname (disqus_shortname) to the disqus config file
	
    $config['disqus_shortname'] = 'YOUR_SHORTNAME_HERE';

***Note:** Make sure to set disqus_developer to 0 when deploying live site.*

### Usage 

Add the below code into your view. 

    $this->disqus->get_html();
	
This will embed the JavaScript which loads and displays DISQUS on your site.

## Endnote 

This is the first spark that I have made so feel free to give me any feedback/advice/guidance.

[1]: http://disqus.com/