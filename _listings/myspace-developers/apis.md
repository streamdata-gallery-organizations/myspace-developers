---
name: MySpace Developers
x-slug: myspace-developers
description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
  http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
x-kinRank: "7"
x-alexaRank: "4691"
tags: MySpace Developers
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/apis.md
specificationVersion: "0.14"
apis:
- name: My Space Post Statusmoodcomments Personid Self Statusid
  x-api-slug: my-space
  description: Posts a comment to a status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmoodcomments/{personId}/@self/{statusId}
  tags: Statusmoodcomments,People,Self,StatusId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodcommentspersonidselfstatusid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodcommentspersonidselfstatusid-post-openapi.md
- name: My Space Get Statusmood Personid Selector Friendid History
  x-api-slug: my-space
  description: Returns History Friend.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/{selector}/{friendId}/history
  tags: Statusmood,People,Selector,FriendId,History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorfriendidhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorfriendidhistory-get-openapi.md
- name: My Space Get Statusmood Personid Selector Friendid
  x-api-slug: my-space
  description: Returns a status for Friend.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/{selector}/{friendId}
  tags: Statusmood,People,Selector,FriendId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorfriendid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorfriendid-get-openapi.md
- name: My Space Get Statusmood Personid Selector History
  x-api-slug: my-space
  description: Returns History User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/{selector}/history
  tags: Statusmood,People,Selector,History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselectorhistory-get-openapi.md
- name: My Space Put Statusmood Personid Selector
  x-api-slug: my-space
  description: Updates a status for User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/{selector}
  tags: Statusmood,People,Selector
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselector-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselector-put-openapi.md
- name: My Space Get Statusmood Personid Selector
  x-api-slug: my-space
  description: Returns a status for User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/{selector}
  tags: Statusmood,People,Selector
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselector-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidselector-get-openapi.md
- name: My Space Put Statusmood Personid @supportedmood Moodid
  x-api-slug: my-space
  description: Updates a mood.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/@supportedMood/{moodId}
  tags: Statusmood,People,Supported,Mood,MoodId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmoodmoodid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmoodmoodid-put-openapi.md
- name: My Space Get Statusmood Personid @supportedmood Moodid
  x-api-slug: my-space
  description: Retrieves a mood.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/@supportedMood/{moodId}
  tags: Statusmood,People,Supported,Mood,MoodId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmoodmoodid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmoodmoodid-get-openapi.md
- name: My Space Post Statusmood Personid @supportedmood
  x-api-slug: my-space
  description: Adds a mood.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/@supportedMood
  tags: Statusmood,People,Supported,Mood
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmood-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmood-post-openapi.md
- name: My Space Get Statusmood Personid @supportedmood
  x-api-slug: my-space
  description: Retrieves all supported moods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmood/{personId}/@supportedMood
  tags: Statusmood,People,Supported,Mood
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmood-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0statusmoodpersonidsupportedmood-get-openapi.md
- name: My Space Get Mediaitemcomments Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Retrieves item comments from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaitemcomments/{personId}/@self/{albumId}/{mediaItemId}
  tags: Mediaitemcomments,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemcommentspersonidselfalbumidmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemcommentspersonidselfalbumidmediaitemid-get-openapi.md
- name: My Space Get Mediaitems Personid Videos Supported Categories Categoryid
  x-api-slug: my-space
  description: Retrieves videos for Category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@videos/@supportedcategories/{categoryId}
  tags: MediaItems,People,@videos,Supported,categories,CategoryId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategoriescategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategoriescategoryid-get-openapi.md
- name: My Space Get Mediaitems Personid Videos Supported Categories
  x-api-slug: my-space
  description: Retrieves supported categories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@videos/@supportedcategories
  tags: MediaItems,People,@videos,Supported,categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategories-get-openapi.md
- name: My Space Put Mediaitems Personid Self Videos Mediaitemid
  x-api-slug: my-space
  description: Updates an video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos/{mediaItemId}
  tags: MediaItems,People,Self,@videos,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-put-openapi.md
- name: My Space Get Mediaitems Personid Self Videos Mediaitemid
  x-api-slug: my-space
  description: Retrieves a video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos/{mediaItemId}
  tags: MediaItems,People,Self,@videos,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-get-openapi.md
- name: My Space Post Mediaitems Personid Self Videos
  x-api-slug: my-space
  description: Adds videos from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos
  tags: MediaItems,People,Self,@videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-post-openapi.md
- name: My Space Get Mediaitems Personid Self Videos
  x-api-slug: my-space
  description: Retrieves all the videos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos
  tags: MediaItems,People,Self,@videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-get-openapi.md
- name: My Space Put Mediaitems Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Updates an item from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}/{mediaItemId}
  tags: MediaItems,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-put-openapi.md
- name: My Space Get Mediaitems Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Retrieves an item from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}/{mediaItemId}
  tags: MediaItems,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-get-openapi.md
- name: My Space Post Mediaitems Personid Self Albums
  x-api-slug: my-space
  description: Adds items from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}
  tags: MediaItems,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-post-openapi.md
- name: My Space Get Mediaitems Personid Self Albums
  x-api-slug: my-space
  description: Retrieves items from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}
  tags: MediaItems,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-get-openapi.md
- name: My Space Get Mediaitems Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/@supportedFields
  tags: MediaItems,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemssupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0mediaitemssupportedfields-get-openapi.md
- name: My Space Delete Stream Subscription All
  x-api-slug: my-space
  description: Deletes all subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription/@all
  tags: Stream,Subscription,@all
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionall-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionall-delete-openapi.md
- name: My Space Get Stream Subscription All
  x-api-slug: my-space
  description: Retrieves all subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription/@all
  tags: Stream,Subscription,@all
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionall-get-openapi.md
- name: My Space Delete Stream Subscription Subscriptionid
  x-api-slug: my-space
  description: Deletes a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription/{subscriptionId}
  tags: Stream,Subscription,SubscriptionId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-delete-openapi.md
- name: My Space Put Stream Subscription Subscriptionid
  x-api-slug: my-space
  description: Updates a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription/{subscriptionId}
  tags: Stream,Subscription,SubscriptionId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-put-openapi.md
- name: My Space Get Stream Subscription Subscriptionid
  x-api-slug: my-space
  description: Retrieves a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription/{subscriptionId}
  tags: Stream,Subscription,SubscriptionId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscriptionsubscriptionid-get-openapi.md
- name: My Space Post Stream Subscription
  x-api-slug: my-space
  description: Creates a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////stream/subscription
  tags: Stream,Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscription-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/streamsubscription-post-openapi.md
- name: My Space Get Opensearch Veos
  x-api-slug: my-space
  description: Returns search results for videos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////opensearch/videos
  tags: Opensearch,Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchvideos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchvideos-get-openapi.md
- name: My Space Get Opensearch Images
  x-api-slug: my-space
  description: Returns search results for images.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////opensearch/images
  tags: Opensearch,Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchimages-get-openapi.md
- name: My Space Get Opensearch People
  x-api-slug: my-space
  description: Returns search results for people.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////opensearch/people
  tags: Opensearch,People
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchpeople-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/opensearchpeople-get-openapi.md
- name: My Space Get Profilecomments Personid Self
  x-api-slug: my-space
  description: Retrieves profile comments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/profilecomments/{personId}/@self
  tags: Profilecomments,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0profilecommentspersonidself-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0profilecommentspersonidself-get-openapi.md
- name: My Space Get People Personid Selector Friendid
  x-api-slug: my-space
  description: Retrieves friend data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/people/{personId}/{selector}/{friendId}
  tags: People,People,Selector,FriendId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplepersonidselectorfriendid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplepersonidselectorfriendid-get-openapi.md
- name: My Space Get People Personid Selector
  x-api-slug: my-space
  description: Retrieves user data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/people/{personId}/{selector}
  tags: People,People,Selector
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplepersonidselector-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplepersonidselector-get-openapi.md
- name: My Space Get People Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/people/@supportedFields
  tags: People,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplesupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0peoplesupportedfields-get-openapi.md
- name: My Space Delete Appdata Personid Selector Appid
  x-api-slug: my-space
  description: Deletes a specified user's application data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/appdata/{personId}/{selector}/{appId}
  tags: Appdata,People,Selector,AppId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-delete-openapi.md
- name: My Space Post Appdata Personid Selector Appid
  x-api-slug: my-space
  description: Adds or updates a specified user's application data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/appdata/{personId}/{selector}/{appId}
  tags: Appdata,People,Selector,AppId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-post-openapi.md
- name: My Space Get Appdata Personid Selector Appid
  x-api-slug: my-space
  description: Retrieves all application data for a specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/appdata/{personId}/{selector}/{appId}
  tags: Appdata,People,Selector,AppId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0appdatapersonidselectorappid-get-openapi.md
- name: My Space Post Notifications Personid Self
  x-api-slug: my-space
  description: Sends notification.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/notifications/{personId}/@self
  tags: Notifications,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0notificationspersonidself-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0notificationspersonidself-post-openapi.md
- name: My Space Get Groups Personid
  x-api-slug: my-space
  description: Retrieves the current user's groups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/groups/{personId}
  tags: Groups,People
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0groupspersonid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0groupspersonid-get-openapi.md
- name: My Space Get Groups Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/groups/@supportedFields
  tags: Groups,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0groupssupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0groupssupportedfields-get-openapi.md
- name: My Space Put Albums Personid Self Albums
  x-api-slug: my-space
  description: Update an Album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/albums/{personId}/@self/{albumId}
  tags: Albums,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidselfalbumid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidselfalbumid-put-openapi.md
- name: My Space Get Albums Personid Self Albums
  x-api-slug: my-space
  description: Retrieves an album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/albums/{personId}/@self/{albumId}
  tags: Albums,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidselfalbumid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidselfalbumid-get-openapi.md
- name: My Space Post Albums Personid Self
  x-api-slug: my-space
  description: Adding an Album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/albums/{personId}/@self
  tags: Albums,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidself-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidself-post-openapi.md
- name: My Space Get Albums Personid Self
  x-api-slug: my-space
  description: Retrieves the current user's albums.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/albums/{personId}/@self
  tags: Albums,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidself-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumspersonidself-get-openapi.md
- name: My Space Get Albums Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/albums/@supportedFields
  tags: Albums,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumssupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0albumssupportedfields-get-openapi.md
- name: My Space Get Activities Personid Selector Appid
  x-api-slug: my-space
  description: Retrieves activities created by an application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/{selector}/{appId}
  tags: Activities,People,Selector,AppId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidselectorappid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidselectorappid-get-openapi.md
- name: My Space Get Activities Supported Object Types
  x-api-slug: my-space
  description: Retrieves all supported object types.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedObjectTypes
  tags: Activities,Supported,ObjectTypes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedobjecttypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedobjecttypes-get-openapi.md
- name: My Space Get Activities Supported Verbs
  x-api-slug: my-space
  description: Retrieves all supported verbs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedVerbs
  tags: Activities,Supported,Verbs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedverbs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedverbs-get-openapi.md
- name: My Space Get Activities Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedFields
  tags: Activities,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiessupportedfields-get-openapi.md
- name: My Space Post Activities Personid Self
  x-api-slug: my-space
  description: Creates an activity for the user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/@self
  tags: Activities,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidself-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidself-post-openapi.md
- name: My Space Get Activities Personid Selector
  x-api-slug: my-space
  description: Retrieves all activities for the user or for the friends of the viewer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/{selector}
  tags: Activities,People,Selector
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidselector-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/1-0activitiespersonidselector-get-openapi.md
- name: My Space
  x-api-slug: my-space
  description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
    http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com//
  tags: MySpace Developers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/myspace-developers/master/_listings/myspace-developers/openapi.md
x-common:
- type: x-website
  url: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
- type: x-blog
  url: http://www.myspace.com/pressroom?url=/company+blog/
- type: x-blog-rss
  url: http://myspace.tekgroupweb.com/company+blog/rss.xml
- type: x-crunchbase
  url: http://www.crunchbase.com/company/myspace
- type: x-crunchbase
  url: https://crunchbase.com/organization/myspace
- type: x-github
  url: https://github.com/myspace
- type: x-twitter
  url: https://twitter.com/#!/MySpaceDevTeam
- type: x-twitter
  url: https://twitter.com/Myspace
- type: x-website
  url: http://myspace.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---