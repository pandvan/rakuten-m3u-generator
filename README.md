# Rakuten m3u Generator

## List
[Generated list (italian only)](output/rakuten.m3u)

## Pipeline status
[![GitHub Actions Demo](https://github.com/pandvan/rakuten-m3u-generator/actions/workflows/pipeline.yml/badge.svg)](https://github.com/pandvan/rakuten-m3u-generator/actions/workflows/pipeline.yml)

## Settings
You can configure the Rakuten country by creating a `.env` file in the project root directory.
```shell
cp .env.example .env
<modify .env with your editor>
```

```
.env
----

CLASSIFICATION=it
```

Set the ID of your country.
Supported countries are:
- Switzerland: `ch`
- Germany: `de`
- France: `fr`
- Italy: `it`
- Netherlands: `nl`
- Norway: `no`
- Poland: `pl`
- Romania: `ro`
- United Kingdom: `uk`

_ATTENTION: Rakuten APIs are geo-blocked_
