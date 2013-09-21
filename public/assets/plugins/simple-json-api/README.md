Simple JSON API for WordPress
=============================

Generate a simple, read-only JSON API for any WordPress site. Just install, activate, and visit mysite.com/api/{post_type_name} to see a JSON payload of that post type.

Use any of the params found at <http://codex.wordpress.org/Class_Reference/WP_Query> by including them via the ?querystring to adjust the returned payload.

To query for an individual object, visit mysite.com/api/{post_type_name}/{id}

### TO DO

* Consider not requiring {post_type_name} when requesting a single resource since ID is unique across all types.
* Allow user to adjust the endpoint for the URL (ie "/api")

Please fork and submit a pull request for any proposed changes.
