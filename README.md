# CMSsc4n

 Tool to identify if a domain has got a CMS and determine his version.
 
 At the moment, CMS's supported by CMSsc4n are WordPress,Moodle,Joomla,Drupal and Prestashop.
 
 # Instalation

You can download the latest version of CMSsc4n by cloning the GitHub repository:

<pre> git clone https://github.com/n4xh4ck5/CMSsc4n.git </pre>

Install the dependencies via pip:

<pre> pip install -r requirements.txt </pre>

# Usage

<pre>
python cmssc4n.py -h
usage: cmssc4n.py [-h] [-e EXPORT] [-c CMS] -i INPUT

This tool verifies if the domain is a CMS (Wordpress , Drupal, Joomla, Prestashop or Moodle) and returns the version

optional arguments:
  -h, --help            show this help message and exit
  -e EXPORT, --export EXPORT
                        File in xlsx format which contains the domains want to know if they are a CMS (y/n)
  -c CMS, --cms CMS     Identify a CMS: W-Wordpress, J-Joomla, D-Drupal, M-Moodle or P-PrestaShop.Default:All
  -i INPUT, --input INPUT
                        Input in txt o json with the domains which it wants to analyze
</pre>

# Author

Ignacio Brihuega Rodríguez aka n4xh4ck5

Twitter:  @n4xh4ck5

Web: fwhibbit.es

# Disclamer

The use of this tool is your responsability. I hereby disclaim any responsibility for actions taken with this tool.
