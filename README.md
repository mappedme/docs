## Mappedme startup guide

In order to get started with Mappedme you need to go through 4 simple steps:

1. [Configure domain](#Domain-configuration)
2. [Test Instagram integration](#instagram-integration)
3. [Create location](#creating-location)
4. [Create location post](#creating-post)

### Domain configuration
- Select `New Domain` sidebar option.
- Fill `Domain name` (mandatory). Domain name is used to access your map via _mappedme.app_ domain. If you pick _sampleName_ your domain will be available via _mappedme.app/sampleName_
- Fill `Instagram profile name` (mandatory). Just your Instagram profile name , used to link to your Instagram profile page.
- `Instagram Basic Api Token`. Just copy and paste your generated token

### Instagram integration 

- Test basic Instagram integration.  
Hit `Run Insta Test` button.  
You should receive a simillar result:  
![image](https://github.com/mappedme/docs/assets/157869436/5942c293-5fce-44a0-be96-8048e19f9f65)

- Start Instagram integration process.
Hit `Run Insta integration` button.  
You should receive a simillar result:  
![image](https://github.com/mappedme/docs/assets/157869436/acf594e9-a6ee-4af4-958c-fbfd94cf9284)

Instagram integration is done in the backgorund and usaully it takes a few seconds. It is enough to do that once a day or after adding a new Instagram post. Do not run it too often as your Facebook Instagram API app has tight request limits. 

### Creating location

- Select `Locations` sidebar option.
- Click on `Add` button in _Locations_ section.
- Fill location's _Name_, _Coordinates_ and _Description_ (optional) and hit `Submit` button.

![image](https://github.com/mappedme/docs/assets/157869436/1495895f-5763-44db-8495-6ca8cc4c158e)

Once saved you location should be visibale on your map. Go to _mappedme.app/{yourDomainName}_

![image](https://github.com/mappedme/docs/assets/157869436/fe9ef905-7a86-4bf3-97ab-7f20bfbe6339)

### Creating post

- Select location's `Posts` option
   
![image](https://github.com/mappedme/docs/assets/157869436/efe7360c-dd00-4517-bda3-858144aa419f)

- Click on `Add` button in Posts section.
- Copy your Instagram post full url.

![image](https://github.com/mappedme/docs/assets/157869436/e61f6874-39e8-4dbd-85fe-094f8950c03e)

- Paste Instagram post url and hit `Submit`   

![image](https://github.com/mappedme/docs/assets/157869436/e70a42ed-ed02-41aa-bc41-429038743e7d)

Once saved the photo be visible on your map when you click on the post's location

![image](https://github.com/mappedme/docs/assets/157869436/d138a3e0-d753-4697-b112-99fca35cc89c)

[Integration](./integration.md)
