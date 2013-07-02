HASHTAG
=======
It's a Rails 3.2 application.

Interacting with the Twitter API.
=================================

The application allows users to search Twitter hashtags using terms. The user is
only allowed to search all hashtags, but will not be allowed to post to any user
account(s).

Running the app
---------------

Make sure you are using Ruby 1.9 (.ruby-version included) and then:

| run |
|-----|
| `bundle` |
| `rake` db:create |
| `foreman start` -p 5500 |

Open on http://localhost:5500

Additional Notes
----------------

You will need to set your the environment variables using your own creds.

| Twitter Creds |
|---------------|
| TWITTER_CONSUMER_KEY |
| TWITTER_CONSUMER_SECRET |
| TWITTER_OAUTH_TOKEN |
| TWITTER_OAUTH_TOKEN_SECRET |

| APP TOKEN/SESSION |
|-------------------|
| HASHTAG_TOKEN |
| HASHTAG_SESSION |

Example:
=======
$ export
HASHTAG_TOKEN="12k30490sfos03040400043kj3kj20024ji88999s9sk3k3"


