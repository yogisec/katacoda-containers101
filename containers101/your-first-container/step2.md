> First, let's discuss on a couple of items:
> 
> - My console is still attached...why?
> - Logging is stdout

Let's break out or 'HUP' the server. **Use CTRL-C in the terminal**

Now let's try to start it again, but this time in the background
by using the -d or --detach flag.

 `docker run --detach --publish 80:80 nginx:latest`{{execute}}

Let's make sure it's running again:

Click https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com

> - Remember the question "Does it pull from docker hub each time"? 
> ``docker images``{{execute}}
> - What if I want to see the logs now? (step 5)
