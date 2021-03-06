# Link‐VGI
**LINKing and analyzing Volunteered Geographic Information (VGI) across different platforms**

Public repository of the [Link-VGI](http://www.geog.uni-heidelberg.de/gis/link_vgi.html) pre-conference workshop at [AGILE2016](https://agile-online.org/index.php/conference/conference-2016).

14 June, 2016. Helsinki, Finland

In case you find the materials of this page useful to incorporate them in your research, the authors appreciate citations to the following article:

Juhász L, Rousell A, Jokar Arsanjani J. Technical Guidelines to Extract and Analyze VGI from Different Platforms. Data. 2016; 1(3):15. [doi:10.3390/data1030015](http://dx.doi.org/doi:10.3390/data1030015)


## Hands-on exercises

The purpose of the hands-on session is to cover the basics of interacting with APIs and to extract summary statistics from the datasets acquired.
All materials can be found in the [Tutorial](workshop/tutorial.md).

## Before the Workshop

### Installing software requirements

In order to connect to and export data from APIs, you will need to install some software components. Follow the guides found on [this page](requirements.md) to install components we are going to use during the hands-on session.

### API Keys

A number of examples require the use of APIs for acquiring data and often these require an API key to be provided. To save time in the practical it would be of benefit to sign up for and acquire an API key for the following services:

| Service | Registration address | API address | Parameters needed |
| ------- | -------------------- | ----------- |  ---------------- ||
| Wheelmap.org | [http://wheelmap.org/users/sign_in](http://wheelmap.org/users/sign_in) (it is actually OSM you need to register for) | [Edit profile page](http://wheelmap.org/profile/edit) | `Authentication Token` |
| Flickr |[Yahoo](https://login.yahoo.com/account/create?.src=flickrsignup&.scrumb=0&new=1&.pd=c%3DJvVF95K62e6PzdPu7MBv2V8-&.intl=de&.done=https%3A%2F%2Flogin.yahoo.com%2Fconfig%2Fvalidate%3F.src%3Dflickrsignin%26.pc%3D8190%26.scrumb%3D0%26.pd%3Dc%253DJvVF95K62e6PzdPu7MBv2V8-%26.intl%3Dde%26.done%3Dhttps%3A%2F%2Fwww.flickr.com%2Fsignin%2Fyahoo%2F&specId=yidReg&altreg=0) (need to register for Yahoo or use a yahoo account) | [Create a new application](https://www.flickr.com/services/apps/create/) and then you can check on your [account page](https://www.flickr.com/account/sharing/) under `Your API keys`| `api_key`, `api_secret` |
| Mapillary | [http://www.mapillary.com/map/signup](http://www.mapillary.com/map/signup) You need to create a Mapillary profile | Once logged in, navigate to [http://www.mapillary.com/map/settings/integrations](http://www.mapillary.com/map/settings/integrations) and hit `Register an application`. | `api_key` from `Profile` -> `Integrations` |
| Twitter | Sign up for [Twitter](https://twitter.com/signup?lang=en) | Go to [Twitter Apps](https://apps.twitter.com/) and hit `Create New App`. | `api_key`, `api_secret` | 
| Instagram [optional] | Sign up for [Instagram](http://instagram.com) | Go to [Instagram Developers](https://www.instagram.com/developer/) and Register a new applications | `client_id`, `client_secret` |

If you do not want to sign up for these services, then there will be sample datasets made available, but obviously you will not be able to run the scripts to get data for an area of your choice.

## Testing



