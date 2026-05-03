# SiriusXM

SiriusXM Holdings Inc. is an American broadcasting corporation providing satellite radio and online audio streaming services in North America. The company offers subscription-based satellite radio, the Pandora streaming music service, and business music services. SiriusXM does not offer a public developer API.

- **Website:** https://www.siriusxm.com
- **Corporate:** https://corporate.siriusxm.com
- **Business Services:** https://www.siriusxm.com/business
- **Pandora:** https://www.pandora.com
- **Investor Relations:** https://ir.siriusxm.com

## Company Overview

SiriusXM was formed by the 2008 merger of Sirius Satellite Radio and XM Satellite Radio. The company:
- Operates the only licensed satellite radio service in the US
- Acquired Pandora in 2019, adding internet radio and on-demand streaming
- Has more than 100 million cars on the road with SiriusXM receivers
- Offers 150+ channels of music, sports, news, comedy, and talk programming
- Reports approximately 33 million subscribers and $8.5 billion annual revenue

## API Availability

SiriusXM does not offer a public REST API for developers. Content is accessed through:
- Consumer subscription apps (iOS, Android, web player)
- In-vehicle satellite radio receivers (OEM partnerships)
- SiriusXM for Business licensing program

An unofficial community API is available at https://xmplaylist.com/docs for channel/track metadata (not affiliated with SiriusXM).

## JSON Schema

| Name | Description |
|---|---|
| [Channel Schema](json-schema/siriusxm-channel-schema.json) | Schema representing a SiriusXM radio channel |

## JSON-LD

| Name | Description |
|---|---|
| [SiriusXM Context](json-ld/siriusxm-context.jsonld) | JSON-LD context mapping SiriusXM terms to schema.org |

## Vocabulary

| Name | Description |
|---|---|
| [SiriusXM Vocabulary](vocabulary/siriusxm-vocabulary.yml) | Domain terms for satellite radio and audio streaming |

## Maintainers

**API Evangelist**
- URL: https://apievangelist.com
- Email: info@apievangelist.com
