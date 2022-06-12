# Table of Issues
This is supposed to contain a table of issues in the current environment with cIMP and cXML

## Overview

|No   	|Issue Name   	|Issue short Description   	|Impact|Usual workaround   	   	|Solution in ONE Record |
|---	|---	|---	|---	|---	|--- |
|1   	|Shipper / Consignee Name / Street  	|Name and street address cannot be transmitted correctly due to length limitation in cXML, cIMP   	|major problems especially with older cIMP with customs clearance etc.	| manual corrections | ✓ fully capable |
|2   	|IOT data, digital checksheets and digital accompanying docs not possible   	|Modern data types like PDFs, geolocations, temperatures, etc. cannot be shared in the current environment using an industry standard	| lack of innovation, loss of efficiency and transparency |bi-lateral generic interfaces   	| ✓  by design |
|3   	|Limits of characters set |cIMP and cXML are limited to [ASCII 7 bit character encoding](https://en.wikipedia.org/wiki/ASCII), which excludes characters like € or ℅ or ° or ‰. Most cIMP fields are limited to A-Z, 0-9 plus minus, dot, space. 	|"c/o" [care of](https://en.wiktionary.org/wiki/care_of) can't be transmitted, "Streetname 3+11" can't be transmitted ...   	|Invalid characters replaced by minus, dot, space with risks, e.g. "Streetname 3-11" is a non-accurate transformation| ✓  fully [Unicode](https://en.wikipedia.org/wiki/Unicode) compatible |
|4   	|SLAC greater than 99.999   	|Length restriction on SLAC number (max 5 digits)	|...   	|...   	| ✓  by design |
|5   	|Precision for small weight  	|Some high value freight has weight where 2nd decimal is required, cXML/cIMP only allows 1 digit	|...   	|...   	|✓  by design |
|6   	|Dimensions, ULDs, HS-Codes limited   	| cIMP: detail data limited to max ±10 data entries in total	| data loss in transmission	| phone / fax / mail…	| ✓ unlimited in 1R |
|7   	|Piece level details and tracking   	| Impossible with cXML/cIMP	| lack of innovation, loss of efficiency and transparency	| phone / fax / mail… | ✓ possible by design |
|8   	|...   	|...	|...   	|...   	|... |
|9   	|...   	|...	|...   	|...   	|... |

## Additional details on 1
## Additional details on 2
## Additional details on 3
## Additional details on 4
## Additional details on 5
