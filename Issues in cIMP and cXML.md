# Table of Issues
This is supposed to contain a table of issues in the current environment with cIMP and cXML

## Overview

|No   	|Issue Name   	|Issue short Description   	|Impact|Usual workaround   	   	|Solution in ONE Record |
|---	|---	|---	|---	|---	|--- |
|1   	|Shipper / Consignee Name / Street  	|Name and street address cannot be transmitted correctly due to length limitation in cXML, cIMP   	|???   	|???   	|Data model is fully capable |
|2   	|IOT data, digital checksheets and digital accompanying docs not possible   	|Modern data types like PDFs, geolocations, temperatures, etc. cannot be shared in the current environment using an industry standard	| lack of innovation, loss of efficiency and transparency |bi-lateral generic interfaces   	|works by design |
|3   	|Limits of characters set |cIMP and cXML are limited to [ASCII 7 bit character encoding](https://en.wikipedia.org/wiki/ASCII), which excludes characters like € or ℅ or ° ‰. Most cIMP fields are limited to A-Z, 0-9 plus minus, dot, space. 	|"C/O" can't be transmitted, "Streetnumber 3+11" can't be transmitted ...   	|Invalid characters replaced by minus, dot, space with risks, e.g. "Streetnumber 3-11" is a non-accurate transformation|Data model is fully [Unicode](https://en.wikipedia.org/wiki/Unicode) compatible |
|4   	|SLAC greater than 99.999   	|Length restriction on SLAC number (max 5 digits)	|...   	|...   	|Data model is fully capable |
|5   	|Precision for small weight  	|Some high value freight has weight where 2nd decimal is required, cXML/cIMP only allows 1 digit	|...   	|...   	|Data model is fully capable |
|6   	|...   	|...	|...   	|...   	|... |
|7   	|...   	|...	|...   	|...   	|... |

## Additional details on 1
## Additional details on 2
## Additional details on 3
## Additional details on 4
## Additional details on 5
