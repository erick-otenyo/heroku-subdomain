# heroku-subdomain
How to Host Sites on a Subdomain with Heroku

# Set up Heroku
Before the content can show up on your site, it needs to be on Heroku. I’m not going to go into how to deploy a site to Heroku, but for this guide you can use any language. I will use python-Django. 

Deploy you app to heroku, lets say you deploy it to my-django-app.herokuapp.com

# Set up your DNS provider
To put content on a subdomain, you need to own a domain name.(I use namecheap)
You also need a way to manage your domain’s DNS. I use the namecheap DNS manager.

I am going to assume you have Namecheap setup and your domain name is tutorial.me

# Connecting your domain to your Heroku app

To point your subdomain at Heroku, add a CNAME record in Namecheap
