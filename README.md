# Dokku Mattermost

Dokku Mattermost is a plugin for [Dokku](https://github.com/progrium/dokku) that notifies [Mattermost](https://about.mattermost.com/) of deployments.

## Installation

# dokku 0.4+
```
$ dokku plugin:install https://github.com/agalisteo/dokku-mattermost
```

## Commands

```sh
$ dokku help
    mattermost:set <app> <webhook_url>                   Set Mattermost WebHook URL
    mattermost:clear <app>                               Clears Mattermost WebHook URL
    mattermost:get <app>                                 Display Mattermost WebHook URL
```

To get **WebHook URL** you need to create a new
[**Incoming WebHook integration**](https://docs.mattermost.com/developer/webhooks-incoming.html).
