Today I learned...
======
#### 2016-07-07 CouchDB
#### 2016-07-04 hello world with Elixir
#### 2016-07-01 to use a git repo as a learning-log
#### 2016-09-20 CakePhp
#### 2016-10-10 LESS
#### 2016-11-15 LocalStorage and sessionStorage both extend Storage. There is no difference between them except for the intended "non-persistence" of sessionStorage. 
#### 2017-03-07 There is no need to use JSON.parse from Javascript, if you are sending json content from server with content-type=application/json. Automaticaly parsed.
#### 2017-03-28 PHP Parse CSV with a single line directly from $_FILES: $csvAsArray = array_map('str_getcsv', file($file['tmp_name']));

#### 2017-05-08 POST a FILE using CURL => 
$args['file'] = new CurlFile('Z_moustache.jpg', 'image/png', 'Z_moustache.jpg');
curl_setopt($ch, CURLOPT_POSTFIELDS, $args);

#### 2017-06-20 Elasticsearch + Kibana Hello World

#### 2017-09-29 Htaccess Redirect including query string. /search will be getting ? GET parameters. RewriteRule ^([a-z]*)/search$ index.php?lang=$1&p=search&m=index&%{QUERY_STRING} 

#### 2017-11-13 Add rel="noopener noreferrer" to target="_blank" links to prevent pishing and to prevent window.opener.location disclosing details of referrer page.

#### 2018-4-5 Easy install of email server, dovecot + sendmail. Be sure to have 127.0.0.1 localhost localhost.localdomain yourdomain.com in /etc/hosts !!!!
