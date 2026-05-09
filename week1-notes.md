how google search works? - from browser to server and back 

so basically what happens here is, when user type any website such as "google.com" (which is plain text - DNS i.e Domain Name System) 
#step 1
  [DNS lookup] which translate "google.com" -> "142.250.74.46" [this involves ISP ->root DNS server-> .com DNS server -> google server]
#step2
  [TCP handshake] establishes reliable connection 
#step3
  [TLS handshake] encrypt the connections (HTTP)
#step4 
  [HTTP GET request] "send me the homepage"
#step5
  [HTTP 200 response] "google send back HTML"
#step6 
  [Browser renders] you can see the google home page
