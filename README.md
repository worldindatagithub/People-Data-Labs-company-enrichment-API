# People Data Labs Company Enrichment API and how to use it #
People Data Labs provides an enrichment API that helps developers identify one-to-one matches for companies. This API can be useful for a variety of purposes, such as verifying business information or building targeted marketing lists. It works by utilizing a proprietary matching algorithm to accurately link companies with their corresponding data records.

[Company Enrichment API](https://www.worldindata.com/api/People-Data-Labs-company-enrichment-api)

Worldindata's API marketplace offers a comprehensive index of third party APIs, making it easier for developers to find the tools they need. The platform aims to make it simpler to understand and utilize these APIs by providing clear documentation and examples of how they can be integrated into projects. With this marketplace, developers can quickly and easily access a wide range of APIs to enhance their products and services.


## Industry, client types, sector for the API ##

**Industry and Sectors**
- b2b marketing
- market analysis
- b2b leads
- business intelligence
- business analysis
- competition analysis
- and more

**Client Types**
- b2b marketers
- business analysts
- business intelligence analysts
- b2b decision makers
- competition intelligence platforms
- and more




## Parameters, Objects and JSON output ##
The GET /v5/company/enrich/ endpoint allows developers to retrieve detailed information about specific companies using the People Data Labs company details API.


**Filter Parameters**
- name
- profile
- ticker
- website
- location
- street_address
- locality
- region
- country
- postal_code
- data_include
- pretty
- api_key
- titlecase
- include_if_matched
- min_likelihood


```
{
  "status": 200,
  "name": "google",
  "size": "10001+",
  "employee_count": 260979,
  "id": "google",
  "founded": 1998,
  "industry": "internet",
  "location": {
    "name": "mountain view, california, united states",
    "locality": "mountain view",
    "region": "california",
    "metro": "san francisco, california",
    "country": "united states",
    "continent": "north america",
    "street_address": "1600 amphitheatre parkway",
    "address_line_2": null,
    "postal_code": "94043",
    "geo": null
  },
  "linkedin_id": "1441",
  "linkedin_url": "linkedin.com/company/google",
  "facebook_url": "facebook.com/google",
  "twitter_url": "twitter.com/google",
  "profiles": [
    "linkedin.com/company/google",
    "linkedin.com/company/1441",
    "facebook.com/google",
    "twitter.com/google",
    "crunchbase.com/organization/google"
  ],
  "website": "google.com",
  "ticker": "GOOGL",
  "type": "public",
  "summary": "google\u2019s mission is to organize the world\u2018s information and make it universally accessible and useful. since our founding in 1998, google has grown by leaps and bounds. from offering search in a single language we now offer dozens of products and services\u2014including various forms of advertising and web applications for all kinds of tasks\u2014in scores of languages. and starting from two computer science students in a university dorm room, we now have thousands of employees and offices around the world. a lot has changed since the first google search engine appeared. but some things haven\u2019t changed: our dedication to our users and our belief in the possibilities of the internet itself.",
  "tags": [
    "online video",
    "artificial intelligence",
    "mobile",
    "android",
    "cloud",
    "machine learning",
    "virtual reality",
    "apps",
    "software",
    "ads"
  ],
  "headline": null,
  "alternative_names": [
    "google inc.",
    "google, social marketing tools",
    "google, inc.",
    "google inc",
    "google, inc",
    "google summer of code",
    "google maps",
    "google ireland",
    "wildfire, a division of google",
    "wildfire interactive, inc."
  ],
  "alternative_domains": [
    "googlevideo.com",
    "google.nl",
    "google.pt",
    "gkecnapps.cn",
    "youtube.com",
    "youtu.be",
    "youtubeeducation.com",
    "gstatic.cn",
    "youtubekids.com",
    "googleadapis.com"
  ],
  "affiliated_profiles": [
    "youtube",
    "google-cloud",
    "think-with-google",
    "google-ads-",
    "googleworkspace",
    "google-analytics",
    "googlemarketingplatform",
    "google-ad-manager",
    "grow-with-google",
    "google-cloud-partners",
    "google-for-startups",
    "google-small-business",
    "x",
    "google-partners",
    "rework-with-google",
    "googleplaydev",
    "googleadmob",
    "google-user-research.",
    "google-news-initiative",
    "adometry"
  ],
  "likelihood": 4
}

```
**Objects**
- status
- name
- size
- employee_count
- id
- founded
- industry
- location
- name
- locality
- region
- metro
- country
- continent
- street_address
- address_line_2
- postal_code
- geo
- linkedin_id
- linkedin_url

## Software Development Kit ##

The People Data Labs company details API is supported by a range of Software Development Kits (SDKs) in various programming languages, including JAVA, Python, Ruby, PHP, and JavaScript. These SDKs make it easy for developers to integrate the API into their projects and begin accessing company data.


### Legal disclaimer ###
Worldindata is a third-party platform that helps developers connect with data providers and make use of their APIs. While we do not own the data accessed through the company enrichment API from People Data Labs, we are big fans of their product and strive to make the data more user-friendly and accessible for developers. Please note that Worldindata is not responsible for the accuracy or completeness of the data provided through the API, and it is up to the developer to ensure that they are complying with the terms of use set by the data provider.


[Worldindata](https://www.worldindata.com)
