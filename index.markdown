---
title: "Welcome to the User Group Toolkit"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/intro_header_user_group_toolkit2.webp
excerpt: "Empowering Collaboration: Your Open Source Toolset for Building Thriving Communities"
meetup_row:
  - title: "Meetup Room Screen"
    excerpt: "The whole meetup evening on the room screen, from nothing but the Meetup link: pre-show with countdown, welcome and who we are, sponsor and speaker handovers, the break with what is next, the closing with the feedback QR code. Clickable chapters, runs by the clock."
    url: "https://github.com/aws-user-groups-austria/meetup-stream-templates"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
  - title: "Meetup Sync"
    excerpt: "Turns a Meetup event page into one event file: agenda, talks, speakers, hosts and logos, with speaker photos from Sessionize and your own overrides. Also imports your past meetups."
    url: "https://github.com/aws-user-groups-austria/meetup-sync"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
  - title: "Meetup Deck"
    excerpt: "Fills your group's own slide deck for the next meetup: the number, the Meetup header, the host logo, the agenda, the speaker cards, the break, the closing and the next AWS Community Day."
    url: "https://github.com/aws-user-groups-austria/meetup-deck"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
pages_row:
  - title: "A page for every meetup"
    excerpt: "Your group's meetup history on your own website: one page per meetup with talks, speakers, host and agenda, prerendered for search engines, and a quiet Present link for organizers. In use on awscommunity.at."
    url: "https://awscommunity.at/meetups/"
    btn_label: "See it live"
    btn_class: "btn--primary"
  - title: "Your group's event data"
    excerpt: "One folder per meetup with its Meetup link and overrides, plus the group's shared photos, logos, badges and upcoming AWS Community Days. The template is the AWS User Group Vienna's."
    url: "https://github.com/aws-user-groups-austria/meetup-event-vienna"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
  - title: "Attendee badges"
    excerpt: "Badge stickers for your meetups: Leader, Host, Speaker, First-Timer and the new All-Timer for your regular members."
    url: "https://github.com/aws-user-group-toolkit/user-group-templates"
    btn_label: "See the templates"
    btn_class: "btn--primary"
gameday_row:
  - title: "Community GameDay stream"
    excerpt: "The stream kit behind AWS Community GameDay Europe: Remotion templates for a live event across many user groups, with the leaderboard."
    url: "https://github.com/aws-community-gameday-toolkit"
    btn_label: "GameDay toolkit"
    btn_class: "btn--primary"
  - title: "Live plugins"
    excerpt: "Plugins for live sessions: face recognition that introduces whoever is on stage, and live transcription and translation for subtitles."
    url: "https://github.com/aws-community-gameday-toolkit"
    btn_label: "See the plugins"
    btn_class: "btn--primary"
assets_row:
  - title: "Meetup Header Image Generator"
    excerpt: "Create captivating meetup headers"
    url: "https://github.com/aws-user-group-toolkit/image-generator"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
  - title: "User Group Templates"
    excerpt: "Ready-to-use templates for diverse content needs"
    url: "https://github.com/aws-user-group-toolkit/user-group-templates"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
  - title: "Sessionize for your group"
    excerpt: "Read your group's Sessionize data: speakers, photos and talks for your meetup tools."
    url: "https://github.com/aws-user-group-toolkit/otto-mcp-sessionize"
    btn_label: "Read the docs"
    btn_class: "btn--primary"
---

## Run a meetup

{% include feature_row id="meetup_row" %}

{% include feature_row id="pages_row" %}

## Community GameDay and live events

{% include feature_row id="gameday_row" %}

## Content and assets

{% include feature_row id="assets_row" %}

## Latest Blog Posts

{% for post in site.posts limit: 3 %}
  {% include archive-single.html %}
{% endfor %}
