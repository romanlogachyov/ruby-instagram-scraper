А simple module for requests to Instagram without an API key.

### Installation

```sh
$ gem install ruby-instagram-scraper
```

Or with Bundler in your Gemfile.

```ruby
gem 'ruby-instagram-scraper'
```

### Methods

After installation you can do following requests to Instagram:

```ruby
# Search by tag or username:
RubyInstagramScraper.search("gopro")

# Get user media nodes:
RubyInstagramScraper.get_user_media_nodes("gopro")

# Pass an "id" of node to offset:
RubyInstagramScraper.get_user_media_nodes("gopro")

# Get next portion of nodes of same tag by passing last node "id":
RubyInstagramScraper.get_tag_media_nodes( "gopro")
```
