# ![LOGO](logo.png) The Noun Project **flow**ground Connector

## Description

A generated **flow**ground connector for the The Noun Project API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/thenounproject.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:23+03:00

## API Description

Icons for Everything

## Authorization

This API does not require authorization.

## Actions

### Get collection by id

> Returns a single collection

*Tags:* `collection`

#### Input Parameters
* `id` - _required_ - Collection id

### Get collection icons by id

> Returns a list of icons associated with a collection

*Tags:* `collection`

#### Input Parameters
* `id` - _required_ - Collection id
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

### Get collection by slug

> Returns a single collection

*Tags:* `collection`

#### Input Parameters
* `slug` - _required_ - Collection slug

### Get collection icons by slug

> Returns a list of icons associated with a collection

*Tags:* `collection`

#### Input Parameters
* `slug` - _required_ - Collection slug
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

### Get all collections

> Return's a list of all collections

*Tags:* `collections`

#### Input Parameters
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

### Get icon by id

> Returns a single icon

*Tags:* `icon`

#### Input Parameters
* `id` - _required_ - Icon id

### Get icon by term

> Returns a single icon

*Tags:* `icon`

#### Input Parameters
* `term` - _required_ - Icon term

### Get recent icons

> Returns list of most recently uploaded icons

*Tags:* `icons`

#### Input Parameters
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

### Get icons by term

> Returns a list of icons

*Tags:* `icons`

#### Input Parameters
* `term` - _required_ - Icon term
* `limit_to_public_domain` - _optional_ - Limit results to public domain icons only
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

### Get api quota status

> Returns current oauth usage and limits

*Tags:* `oauth`

### Get user collections

> Returns a list of collections associated with a user

*Tags:* `user`

#### Input Parameters
* `user_id` - _required_ - User id

### Get user collection

> Returns a single collection associated with a user

*Tags:* `user`

#### Input Parameters
* `user_id` - _required_ - User id
* `slug` - _required_ - Collection slug

### Get user uploads with user

> Returns a list of uploads associated with a user

*Tags:* `user`

#### Input Parameters
* `username` - _required_ - Username
* `limit` - _optional_ - Maximum number of results
* `offset` - _optional_ - Number of results to displace or skip over
* `page` - _optional_ - Number of results of limit length to displace or skip over

## License

**flow**ground :- Telekom iPaaS / thenounproject-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
