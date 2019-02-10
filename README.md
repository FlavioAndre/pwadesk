PWA Desktop

npm install -g http-server
instalar certificado

 openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
ReviewCertificate: openssl x509 -text -noout -in cert.pem
Combinar com p12: openssl pkcs12 -inkey key.pem -in cert.pem -export -out cert.p12
validar: openssl pkcs12 -in cert.p12 -noout -info

https://www.ibm.com/support/knowledgecenter/en/SSWHYP_4.0.0/com.ibm.apimgmt.cmc.doc/task_apionprem_gernerate_self_signed_openSSL.html

http-server -S -C cert.pem -o

Gerar manifest.json
buscar no google por firebase manifest.json
https://app-manifest.firebaseapp.com/

generate icon http://www.xiconeditor.com

instalar no chrome web store Ligthouse, gera relatório se aplicação está 100% PWA ou usar o Audits do inspect do chrome

sugestão pegar fonts no Google Fonts, que garante que não irá ter problemas com direitos autorais
https://fonts.google.com

animate css cdnjs  https://cdnjs.com/libraries/animate.css/

css degrade background generator
http://www.colorzilla.com/gradient-editor/

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

