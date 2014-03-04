capture stuff from the android app

1. install the philips hue software (https://play.google.com/store/apps/details?id=com.philips.lighting.hue) on an android phone
2. install shark for root (https://play.google.com/store/apps/details?id=lv.n3o.shark) on the android phone.
3. start shark for root capture
4. go to hue software and do something
5. stop shark for root capture
6. install wireshark (http://www.wireshark.org/) on desktop
7. open pcap file from android capture in wireshark
8. filter the results with "http.request.method == "PUT"" to see what the android app commands are
