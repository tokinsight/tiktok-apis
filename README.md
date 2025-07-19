# TokInsight - UnLock TikTok's Data Power

## 🚀 Overview

TokInsight is a powerful TikTok API platform that provides comprehensive data insights and original data for TikTok content creators, marketers, and businesses. Our platform offers real-time access to TikTok's vast data ecosystem through a robust REST API. Including **Profile**, **Device**, **Video**, **Music**, **Comment**, **Hashtag**, **Collection(Mix)**, **Trending**, **Search**, **Live**, **Shop**, **Place**, **Effect**, etc. 


## 📞 Contact Information
- **Email**: tokinsight@protonmail.com
- **Discord**: https://discord.gg/CDPse7dYhh
- **All in One API Service**: https://rapidapi.com/tokinsight/api/tokinsight1
- **Device API Service**: https://rapidapi.com/tokinsight/api/tiktok-device

## ✨ Key Features

### 📊 **Comprehensive Analytics**
- **User Analytics**: Profile insights, follower analysis, engagement metrics
- **Content Analytics**: Video performance, trending analysis, hashtag tracking
- **Market Intelligence**: Competitor analysis, industry trends, audience insights
- **Real-time Data**: Live updates and real-time monitoring capabilities

### 🎯 **Business Intelligence**
- **Audience Insights**: Detailed demographic and behavioral analysis
- **Content Strategy**: Data-driven content recommendations
- **Performance Tracking**: Monitor campaign effectiveness and ROI
- **Competitive Analysis**: Benchmark against competitors and industry standards

## 🛠️ API Capabilities

### **User Analytics Endpoints**
- `GET /tok/v1/user_uniqueid/` - Get user ID from unique identifier
- `GET /tok/v1/user_profile/` - Retrieve detailed user profiles
- `GET /tok/v1/user_following/` - Get user's following list
- `GET /tok/v1/user_follower/` - Get user's followers list
- `GET /tok/v1/user_video/` - Retrieve user's video content
- `GET /tok/v1/user_favorite_video/` - Get user's favorite videos
- `GET /tok/v1/user_mix_list/` - Access user's mix collections
- `GET /tok/v1/user_mix_detail/` - Get detailed mix information

### **Content Analytics Endpoints**
- `GET /tok/v1/video_detail/` - Get comprehensive video analytics
- `GET /tok/v1/comment_list/` - Retrieve video comments
- `GET /tok/v1/comment_reply_list/` - Get comment replies
- `GET /tok/v1/hashtag_detail/` - Analyze hashtag performance
- `GET /tok/v1/hashtag_video/` - Get videos by hashtag

### **Search & Discovery Endpoints**
- `GET /tok/v1/search_video/` - Search for videos by keyword
- `GET /tok/v1/search_user/` - Find users by keyword
- `GET /tok/v1/search_hashtag/` - Discover trending hashtags
- `GET /tok/v1/search_music/` - Find music tracks
- `GET /tok/v1/search_live/` - Discover live streams
- `GET /tok/v1/search_trending_list/` - Get trending content

### **Music Analytics Endpoints**
- `GET /tok/v1/music_original_list/` - Access original music content
- `GET /tok/v1/music_detail/` - Get music track analytics
- `GET /tok/v1/music_video/` - Find videos using specific music
- `GET /tok/v1/music_pinned_pgc_list/` - Get pinned music lists

### **Device Registration Endpoints**
- `GET /tok/v1/register_device_one/` - Register one device and get the device info


### **More Endpoints ...**


## 🔧 Technical Specifications
**01 example of get uid and sec_uid from unique_id (nickname)**
```json
{
  "extra": {
    "fatal_item_ids": [],
    "logid": "202506301742**********",
    "now": 175130**********
  },
  "sec_uid": "MS4wLjABAAAAynsS7I31Vgq5E7lOOvChbUheLkv6v**************",
  "status_code": 0,
  "status_msg": "",
  "uid": "685099556791******"
}
```

**02 example of get user profile**
```json
{
    "extra": {
      "fatal_item_ids": [],
      "logid": "20250708000732A6716855F*****",
      "now": 17519044***
    },
    "status_code": 0,
    "status_msg": "",
    "user": {
      "account_labels": [
        {
          "content": "Artist",
          "label_type": 3
        }
      ],
      "account_type": 0,
      "ad_virtual": false,
      "avatar_168x168": {
        "uri": "tos-useast5-avt-0068-tx/0b55af0c74e15eeb19089946589c55a9",
        "url_list": [
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:168:168.webp?dr=14577&refresh_token=5e6d2e72&x-expires=1752076800&x-signature=EN2Bs92l3wmoelZZPP6f69m5wbw%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva",
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:168:168.jpeg?dr=14577&refresh_token=074e8421&x-expires=1752076800&x-signature=eCDSeQdkeK5vrErnfvXGd4JuuTc%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva"
        ],
        "url_prefix": null
      },
      "avatar_300x300": {
        "uri": "tos-useast5-avt-0068-tx/0b55af0c74e15eeb19089946589c55a9",
        "url_list": [
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:300:300.webp?dr=14577&refresh_token=e2b69cef&x-expires=1752076800&x-signature=GvokXYRdWRAOdjRlFFb9CZJf1EA%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva",
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:300:300.jpeg?dr=14577&refresh_token=44c15700&x-expires=1752076800&x-signature=v%2Bv4dDXZ0LMz%2BgWr%2BijcY8hDQpY%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva"
        ],
        "url_prefix": null
      },
      "avatar_larger": {
        "uri": "tos-useast5-avt-0068-tx/0b55af0c74e15eeb19089946589c55a9",
        "url_list": [
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:1080:1080.webp?dr=14579&refresh_token=b7fb3034&x-expires=1752076800&x-signature=lbavmhpsuo2DGXF6%2Bf42A%2FB0B3o%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva",
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:1080:1080.jpeg?dr=14579&refresh_token=c3a49c01&x-expires=1752076800&x-signature=Cml7WeyWbj254kZXk50Pe7vzHk8%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva"
        ],
        "url_prefix": null
      },
      "avatar_medium": {
        "uri": "tos-useast5-avt-0068-tx/0b55af0c74e15eeb19089946589c55a9",
        "url_list": [
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:720:720.webp?dr=14579&refresh_token=2a523df4&x-expires=1752076800&x-signature=Qk%2FDTXBejXD4vKI5J0%2B%2FMgcWtZ0%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva",
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:720:720.jpeg?dr=14579&refresh_token=91b91037&x-expires=1752076800&x-signature=4KxdYEcAZF4KJ7zyQGgvReTqiJ8%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=2472a6c6&idc=maliva"
        ],
        "url_prefix": null
      },
      "avatar_thumb": {
        "uri": "tos-useast5-avt-0068-tx/0b55af0c74e15eeb19089946589c55a9",
        "url_list": [
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:100:100.webp?dr=14579&refresh_token=3f581870&x-expires=1752076800&x-signature=tMJ85fwH2iLeU7GFWyDZjeAD6rE%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=dafad184&idc=maliva",
          "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/0b55af0c74e15eeb19089946589c55a9~tplv-tiktokx-cropcenter:100:100.jpeg?dr=14579&refresh_token=8eec2a03&x-expires=1752076800&x-signature=r3FTo0sjSHfB%2FD1ovR7GrkLMIL8%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=dafad184&idc=maliva"
        ],
        "url_prefix": null
      },
      "aweme_count": 6,
      "category": "",
      "commerce_user_info": {
        "ad_revenue_rits": null
      },
      "commerce_user_level": 0,
      "custom_verify": "verified account",
      "enterprise_verify_reason": "",
      "favoriting_count": 0,
      "follow_status": 0,
      "follower_count": 25344079,
      "follower_status": 0,
      "following_count": 88,
      "forward_count": 0,
      "has_open_favorite": false,
      "ins_id": "",
      "is_acquaintance": false,
      "is_block": false,
      "is_blocked": false,
      "is_effect_artist": false,
      "is_star": false,
      "live_commerce": false,
      "live_push_notification_status": 2,
      "message_chat_entry": false,
      "mplatform_followers_count": 0,
      "music_tab_info": {
        "show_artist_pick_videos": false
      },
      "nickname": "Doja**",
      "original_musician": {
        "digg_count": 0,
        "music_count": 1343,
        "music_used_count": 0,
        "new_release_clip_ids": null
      },
      "privacy_setting": {
        "following_visibility": 1
      },
      "profile_tab_type": 0,
      "recommend_reason_relation": "",
      "room_id": 0,
      "sec_uid": "MS4wLjABA*********egmnfJnnKGC2ZfXaC672rP***",
      "secret": 0,
      "share_info": {
        "now_invitation_card_image_urls": null,
        "share_desc": "Check out Doja Cat! #TikTok",
        "share_title": "Join TikTok and see what I’ve been up to!",
        "share_url": "https://www.tiktok.com/@dojacat?_r=1&_d=el4ba9e58di226&sec_uid=MS4wLjABA*********egmnfJnnKGC2ZfXaC672rP7_PwtVK8lPgqC1O-Qh13yqOB9xqhI&share_author_id=6656913964248088581&sharer_language=en&source=h5_m"
      },
      "short_id": "0",
      "show_artist_playlist": 1,
      "show_favorite_list": false,
      "show_messaging_entrance_on_profile": true,
      "signature": "",
      "signature_language": "un",
      "story_status": 0,
      "supporting_ngo": {},
      "tab_settings": {
        "private_tab": {
          "private_tab_style": 1,
          "show_private_tab": false
        },
        "repost_tab": {
          "repost_tab_all_visible": true,
          "show_repost_tab_other": 1
        }
      },
      "total_favorited": 4161692,
      "twitter_id": "",
      "twitter_name": "",
      "uid": "66569139642480***",
      "unique_id": "dojat",
      "verification_type": 1,
      "visible_videos_count": 6,
      "watch_status": false,
      "with_commerce_enterprise_tab_entry": false,
      "with_commerce_entry": false,
      "with_new_goods": false,
      "youtube_channel_id": "",
      "youtube_channel_title": ""
    }
  }
```

**03 exploring more via tokinsight apis**
...


### **Coming Soon**
- 🔄 support of live
- 🔄 support of shopping
