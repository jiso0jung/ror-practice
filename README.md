# Ruby on Rails 시작하기

https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one
* 프로젝트 설정 로드되지 않던 현상 -> 프로젝트가 읽기적용으로 생성됨. chmod -R 777 루트디렉토리 적용
* 테스트 정상 진행되지 않던 현상 -> rspec 3.5에서 4.0으로 버전업 후 해결
* 테스트 시 support 하위파일 정상반영되지 않던 현상 -> Rspec.configuration 삭제 및 하위내용 Rspec.configure에 통합
