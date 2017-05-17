# Someecards OEmbed Documentation

### API Endpoint

* https://www.someecards.com/v2/oembed/

### Parameters:

* `url` - accepted formats:
  * https://www.someecards.com/.+-cards/*
  * https://www.someecards.com/usercards/viewcard/*
  * https://some.ly/*
* `format`
  * Currently `json` is supported

### Example:

* https://www.someecards.com/v2/oembed/?format=json&url=https%3A//www.someecards.com/apology-cards/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day/&callback=jQuery31107255120558535322_1492712170545&_=1492712170546
```
/**/jQuery31107255120558535322_1492712170545(
{
  type: "rich",
  title: "Sorry that I went in for a fist bump on National High Five Day.",
  url: "https://cdn.someecards.com/someecards/filestorage/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day-vbA.png",
  thumbnail_url: "https://cdn.someecards.com/someecards/filestorage/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day-vbA.png",
  thumbnail_width: 425,
  thumbnail_height: 237,
  width: 425,
  height: 237,
  web_page: "https://www.someecards.com/apology-cards/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day/",
  html: "<blockquote class="someecards-embed" id="card-embed-4160207" data-id="4160207" data-url="https://www.someecards.com/embed/card/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day/?type=card"><a href="https://www.someecards.com/apology-cards/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day/" target="_blank"><img class="img-responsive" src="https://cdn.someecards.com/someecards/filestorage/sorry-that-i-went-in-for-a-fist-bump-on-national-high-five-day-vbA.png" alt="Sorry that I went in for a fist bump on National High Five Day." /></a></blockquote><script async src="//cdn.someecards.com/assets/embed/embed-v1.04.min.js" charset="utf-8"></script>",
  author_url: "https://www.someecards.com/page/about",
  author_name: "someecards"
}
```
