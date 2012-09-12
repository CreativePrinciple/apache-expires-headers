# ![Creative Principle](http://creativeprinciple.com.au/logo2.png)
# Apache Expires Headers


    # compress text, html, javascript, css, xml:
    AddOutputFilterByType DEFLATE text/plain
    AddOutputFilterByType DEFLATE text/html
    AddOutputFilterByType DEFLATE text/xml
    AddOutputFilterByType DEFLATE text/css
    AddOutputFilterByType DEFLATE application/xml
    AddOutputFilterByType DEFLATE application/xhtml+xml
    AddOutputFilterByType DEFLATE application/rss+xml
    AddOutputFilterByType DEFLATE application/javascript
    AddOutputFilterByType DEFLATE application/x-javascript

    # Or, compress certain file types by extension:
    <files *.html>
    SetOutputFilter DEFLATE
    </files>

## htaccess time cheatsheet 
	#      300   5 MIN
	#      600  10 MIN
	#      900  15 MIN
	#     1800  30 MIN
	#     2700  45 MIN
	#     3600   1 HR
	#     7200   2 HR
	#    10800   3 HR
	#    14400   4 HR
	#    18000   5 HR
	#    36000  10 HR
	#    39600  11 HR
	#    43200  12 HR
	#    46800  13 HR
	#    50400  14 HR
	#    54000  15 HR
	#    86400   1 DAY
	#   172800   2 DAY
	#   259200   3 DAY
	#   345600   4 DAY
	#   432000   5 DAY
	#   518400   6 DAY
	#   604800   1 WEEK
	#  1209600   2 WEEK
	#  1814400   3 WEEK
	#  2419200   4 WEEK
	#  4838400   2 MONTH
	#  7257600   3 MONTH
	#  9676800   4 MONTH
	# 12096000   5 MONTH
	# 14515200   6 MONTH
	# 16934400   7 MONTH
	# 19353600   8 MONTH
	# 21772800   9 MONTH
	# 24192000  10 MONTH
	# 26611200  11 MONTH
	# 29030400  12 MONTH	
	
	
## Resources  
* http://httpd.apache.org/docs/2.2/mod/mod_expires.html
* http://www.askapache.com/hacking/speed-site-caching-cache-control.html