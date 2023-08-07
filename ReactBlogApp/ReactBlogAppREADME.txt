
REACT BLOG APP KULLANIM KLAVUZU

Kaynak Link : https://www.youtube.com/watch?v=0aPLk2e2Z3g&list=PLs4HAN45M-eQeH6epirBmk50SDSdCVW6T&index=1

Kaynak Proje : https://github.com/safak/youtube2022/tree/blog-app

React blog app yapılması gerekenler: 

1 ) blog adında sql database olustur.

2) 2 adet tablomuz var. sqlcommands klasöründeki fotoğraflardaki sql komutlarını çalıştır 

3) Terminali açıp cd client adresine gidip yarn komutunu calıstır veya npm install kullanabilirsin paketleri yüklemek için.

4) Terminali açıp cd api adresine gidip yarn komutunu calıstır veya npm install kullanabilirsin paketleri yüklemek için.

5) import from mysql -> olan yerleri import from mysql2 ile değiştir öncesinde yarn add mysql2 veya npm install mysql2 yap cd api yolunda

6) process.env.DB_KEY yazan yere -> database passwordunu yap

7) Son olarak 2 adet terminal açıp cd client ve cd api adreslerine gidip ayrı ayrı npm start yaz.

NOT : yarn kurulumu npm ile yapılıyor fakat command windowdan tek seferlik ekstra bi izin kodu yazmak gerekiyor !!!

NOT : projede adresine cd ile gidince ve sadece yarn komutunu calıstırınca json package deki paketlerin hepsini yüklüyor !!!