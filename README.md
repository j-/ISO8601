# ISO 8601

## Formatting

### JavaScript

#### [Moment.js](http://momentjs.com/docs/)

##### v2.13.0

Default format returns `Z` as the offset instead of `+00:00` when in UTC mode.

##### v2.7.0

Supports a [`moment.ISO_8601`](http://momentjs.com/docs/#/parsing/special-formats/) constant which represents the ISO 8601 format for parsing date/time strings.

##### v1.5.0

Supports ISO 8601 as the default format.

##### v1.2.0

    YYYY-MM-DDTHH:mm:ssZ

Formats a date/time value in ISO 8601 time zone designator format (`Z` or `+hh:mm` or `-hh:mm`).

##### All versions

    YYYY-MM-DDTHH:mm:ss[Z]

Explicitly formats a date/time value in ISO 8601 Zulu time format (`Z`).

## Links

* ['ISO 8601' on Wikipedia](https://en.wikipedia.org/wiki/ISO_8601)
* ['Date and Time Formats' on W3C](https://www.w3.org/TR/NOTE-datetime)
* ['ISO 8601' on xkcd](https://xkcd.com/1179/)
