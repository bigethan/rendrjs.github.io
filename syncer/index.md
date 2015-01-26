---
layout: content
title: "Syncer - RendrJS"
---

# Syncer

The syncer methods are mixins used in the [**models**](/model) and [**collections**](/collection) to simplify data retrival from an API.  The syncer is setup to work on requests that are started on the client or server.  It automatically adds the any API prefixes defined, and makes the reqeusts.  It is modeled after the [**model sync**](http://backbonejs.org/#Model-sync) and [**collection sync**](http://backbonejs.org/#Collection-sync) created in Backbone.

The most important thing to note about the syncer methods and attributes is since they are mixed into models and collections, all of them are available on both models and collections.

{% for doc in site.syncer %}
  <h3 id="{{doc.header}}">
    <a href="#{{doc.header}}">{{ doc.header }}</a>
    <span>{{ doc.example }}</span>
  </h3>

  <hr />
  {{doc.content}}
{% endfor %}
