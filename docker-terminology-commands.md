| Komut       | Örnek                                                                                                  | Açıklama                                                                  |
|-------------|--------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| create      | docker volume create <volume_name>                                                                     | Bir şeyi oluşturmak için kullanılır                                       |
| inspect     | docker volume inspect <volume_name>                                                                    | Özellik hakkında detaylı bilgi erişmek için kullanılır                    |
| ls          | docker volume ls                                                                                       | Özellik ait oluşturulan verilerin listenmesi için kullanılır              |
| prune       | docker volume prune                                                                                    | Özelliğin tümünü kısmi veya tümünü kaldırmak için kullanılır.             |
| rm          | docker volume rm                                                                                       | Özelliği silmek için kullanılır                                           |
| detach (-d) | docker run -d                                                                                          | Özelliği arkaplanda çalıştırmak için kullanılır                           |
| attach (-a) | docker container <container>                                                                           | Özelliği input/output çıktılarını takip etmek içindir                     |
| diff        | docker container diff <container>                                                                      | Özelliğin mevcut durumundan, çalışma zamanında değişen farkları gösterir. |
| exec        | docker exec <container>                                                                                | Çalışan özellikle alakalı bağlantı kurarak bir şeyler yapmak içindir.     |
| file (-f)   | docker build -f ./DockerFiles/Dockerfile.debug .                                                       | Özelliğin ihtiyacı olan dosyayı belirtmek için kullanılır.                |
| exit        | docker exec -it <container_name> /bin/bash //terminal erişimi sağlandı<br/> exit //terminalden çıkıldı | exit                                                                      |
| port (-p)   | docker run -p 8000:80 <image_name>                                                                     | Özelliğe port belirlemek için kullanılır.                                 |
| \           | apt-get update && \\ <br/>apt-get install                                                              | Alt satıra geçmek için kullanılır.                                        |
