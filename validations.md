## ENUMS

The language codes in:
`agencies.agency_lang`
`feed_info.default_lang`
`feed_info.feed_lang`
`translations.language`

Must be defined according to the 2 lower case letter [ISO 639-1 Code](https://www.loc.gov/standards/iso639-2/php/code_list.php) standard, with the exception of `mul` for multilanguage.

The currency codes in: `fare_attributes.currency`

Must be defined according to the 3 upper case letter active [ISO 4217 Code](https://en.wikipedia.org/wiki/ISO_4217#Active_codes)

The timezones in: `agencies.agency_timezone` `stop_times.stop_timezone`

Must be specified according to the current [TZ database](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones).

They must be in the `Region/(zone)/City` format, generic `Factory`/ `Etc/*` / `GMT` / `UTC` are not accepted.

Deprecated timezones are not accepted.
