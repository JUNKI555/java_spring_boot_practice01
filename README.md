# Java Spring Boot Practice 01

# EndPointList

## HTML EndPoint
- http://localhost:8080/

## Web API EndPoint
- curl http://localhost:8080/test -X GET
  - ok from test.
- curl http://localhost:8080/test/json -X GET
  - {"value1":"foo","value2":"bar"}
- curl http://localhost:8080/test/post -X POST -H 'Content-Type: application/json' -d '{"value1":"hoge","value2":"fuga"}'
  - {"value1":"hoge:AddServer","value2":"fuga:AddServer"}

## Reference sources
- docker-compose 下で Java + Spring Boot 環境を作ってみる | 北山淳也 | zenn
  - https://zenn.dev/junki555/articles/1073408293050f
- docker-compose 下で Java + Spring Boot + Thymeleaf を試す | 北山淳也 | zenn
  - https://zenn.dev/junki555/articles/4358b1c7ca169d
- docker-compose 下で Java + Spring Boot + 簡単なWeb API を作ってみる | 北山淳也 | zenn
  - https://zenn.dev/junki555/articles/a19f27d1045805
- OpenJDK | DockerHub
  - https://hub.docker.com/_/openjdk
- JDK Project Releases | OpenJDK
  - http://openjdk.java.net/projects/jdk/
- Spring Initializr
  - https://start.spring.io/
- Docker × Spring Boot環境構築 | Qiita
  - https://qiita.com/A-Kira/items/beaf79a0d39d9839e61e
- SpringBootに入門する為の助走本（随時更新） | Qiita
  - https://qiita.com/sugaryo/items/5695bfcc21365f429767
- Spring Boot触ってみる その2 ーController,テンプレートエンジン(Thymeleaf)ー | endokのブログ
  - http://endok.hatenablog.com/entry/2016/06/06/035849
- Spring Boot RestControllerメモ(Hishidama's Spring Boot RestController Memo) | ひしだま's ホームページ
  - https://www.ne.jp/asahi/hishidama/home/tech/java/spring/boot/rest/RestController.html
- Difference between @RestController and @Controller Annotation in Spring MVC and RESTをテキトーに訳した | kagamihogeの日記
  - https://kagamihoge.hatenablog.com/entry/2017/09/17/171905
- REST コントローラーの作成 - @RestController | 独習Spring
  - https://yo1000.gitbooks.io/self-study-spring/content/appendix1.html
