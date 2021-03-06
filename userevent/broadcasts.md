### **event/broadcasts/{eventID}**

Deployed on branch: `api` `dev`

#### **Description**

Returns all the broadcasts for an event

#### **Method**

GET

#### **Param**

- access_token
- eventID
- offset: default 0
- limit: default 10
- Paramx: simple explanation

Example:
http://api.evan.dev.charged.fm/userevent/broadcasts/23

```javascript
{
    "limit": 10,
    "offset": 0,
    "totalBroadcasts": 3,
    "event": {
        "usereventid": "23",
        "title": "DJ Jake's Hip-Hop Spectacular",
        "startDate": "2011-08-01 10:30 PM",
        "venueName": "The Palace",
        "host": "Jake",
        "userID": "97",
        "username": "jake.langbecker@gmail.com",
        "displayName": "langbecker",
        "fullName": "Jake Langbecker",
        "eventType": "userevent"
    },
    "broadcasts": [
        {
            "id": "19",
            "caption": "Here's+a+caption%2Bdude1%2B",
            "totalLikes": "0",
            "totalComments": "0",
            "dateCreated": "2014-12-30T17:04:29-05:00",
            "user": {
                "id": "113429",
                "fullName": "Evan Ridenour",
                "displayName": "evride"
            },
            "images": {
                "thumbnail": {
                    "width": "150",
                    "height": "150",
                    "url": "1419977069_oHMJrteD_thumbnail.jpg"
                },
                "standard": {
                    "width": "640",
                    "height": "640",
                    "url": "1419977069_oHMJrteD_standard.jpg"
                },
                "full": {
                    "width": "960",
                    "height": "960",
                    "url": "1419977069_oHMJrteD_full.jpg"
                }
            }
        },
        {
            "id": "22",
            "caption": "Derpy derpy",
            "totalLikes": "0",
            "totalComments": "0",
            "dateCreated": "2015-01-06T14:22:27-05:00",
            "user": {
                "id": "113429",
                "fullName": "Evan Ridenour",
                "displayName": "evride"
            },
            "images": {
                "thumbnail": {
                    "width": "150",
                    "height": "150",
                    "url": "1420572144_CnREQnBH_thumbnail.jpg"
                },
                "standard": {
                    "width": "640",
                    "height": "640",
                    "url": "1420572144_CnREQnBH_standard.jpg"
                },
                "full": {
                    "width": "960",
                    "height": "960",
                    "url": "1420572144_CnREQnBH_full.jpg"
                }
            }
        },
        {
            "id": "23",
            "caption": "Derpy derpy",
            "totalLikes": "0",
            "totalComments": "0",
            "dateCreated": "2015-01-06T14:28:26-05:00",
            "user": {
                "id": "113429",
                "fullName": "Evan Ridenour",
                "displayName": "evride"
            },
            "images": {
                "thumbnail": {
                    "width": "150",
                    "height": "150",
                    "url": "1420572503_Bd0v7jO2_thumbnail.jpg"
                },
                "standard": {
                    "width": "640",
                    "height": "640",
                    "url": "1420572503_Bd0v7jO2_standard.jpg"
                },
                "full": {
                    "width": "960",
                    "height": "960",
                    "url": "1420572503_Bd0v7jO2_full.jpg"
                }
            }
        }
    ]
}
```
