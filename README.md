# Graylog extractors

# 30/08/2018: Added extractors for Apache

# Example log:

93.33.22.11 - - [27/Aug/2018:09:37:57 +0200] "GET /js/jquery/jquery.js HTTP/1.1" 304 - "https://mywebsite.com/app/node.js" "Mozilla/5.0 (Windows NT 10.0; WOW64; rv:52.0) Gecko/20100101 Firefox/52.0"

# Extracted fields :

Apache_date Regular expression

Apache Client IP Split & Index (space)

Apache Time Regular expression

Apache http request Split & Index(")

Apache referrer Split & Index (")

Apache user agent Split & Index (")

Apache http status code Regular expression
