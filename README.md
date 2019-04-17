# Motif Web Admin Template Project

This is the project starter for the MOTIF Web Admin Console.

## Installation

<strong>1</strong>. Clone this repository

```terminal
git clone  https://github.com/github-vipera/motif-web-admin-template-project.git MyWebAdmin
```

<strong>2</strong>. Install dependencies

```terminal
cd MyWebAdmin
npm install
```

<strong>3</strong>. Change Proxy configuration

Open ```proxy.conf.json``` file and change the URL to point to your MOTIF Server instance:

```json
{
    "/rest": {
      "target": "http://my.motif.instance:8080/",
      "secure": false,
      "logLevel": "debug"
    },
    "/oauth2": {
      "target": "http://my.motif.instance:8080/",
      "secure": false,
      "logLevel": "debug"
    }
  }
```

<strong>4</strong>. Run

```terminal
ng serve
```

at the end of the procedure go to http://localhost:42000







