![Communibase](https://www.communibase.nl/img/siteLogo.png "Communibase")

# Wordpress Communibase API Plugin

Adds Communibase API support to Wordpress.

[Communibase](https://www.communibase.nl) is a paid service for membership administration. See [https://www.communibase.nl](https://www.communibase.nl) for connection details.

This plugin currently adds a setting screen for setting the API-key / host and a `WP_Communibase_Connector` delegate that can be used to access the API.
`WP_Communibase_Connector` delegates to the [Communibase PHP API Connector](https://github.com/kingsquare/communibase-connector-php). The delegate currently only adds a [Transient_API](https://codex.wordpress.org/Transients_API) caching layer and a few convenience methods. It is possible to use the `\Communibase\Connector` directly.

Status: WIP

## TODO

 - [x] add license
 - [ ] WP Coding Standards https://make.wordpress.org/core/handbook/best-practices/coding-standards/
 - [ ] CI (wercker?)
   - [ ] tests (against top x (5?) wordpress versions)
   - [ ] build & publish dist to [wordpress plugin directory](https://wordpress.org/plugins/developers/add/)
    - [ ] http://jeremypry.com/wordpress-plugin-development-with-github/
