# JSONView-for-Chrome

Validate and view JSON documents

Features: 
- JSON is validated using a client-side javascript implementation of JSONLint (http://github.com/zaach/jsonlint)
- this extension displays JSON text compliant with rfc 4627 (http://www.ietf.org/rfc/rfc4627.txt).
- JSONP (http://en.wikipedia.org/wiki/JSON#JSONP) is supported
- Base on https://github.com/gildas-lormeau/JSONView-for-Chrome
- Open https://www.json.cn/ when clicking the icon



You can configure JSON parsing method in options page:
- the default method (JSON content is extracted from displayed page) is faster but can (in some rare cases) alter or fail to parse the JSON content.
- the safe method costs an extra XMLHttpRequest request (JSON content is extracted from the HTTP response) but is 100% safe.
