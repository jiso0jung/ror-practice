# Ruby on Rails 시작하기

## Part 1
https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one
#### 오류 내용
* rubymine에서 프로젝트 설정 로드 불가
  * 프로젝트가 read-only 로 생성되었기 때문. chmod -R 777 루트디렉토리 적용
* 테스트 진행 오류
  * rspec 3.5에서 4.0으로 버전업 후 해결
* 테스트 시 support 하위파일 미반영
  * spec_helper.rb에서 Rspec.configuration 삭제 및 하위내용 Rspec.configure에 통합
