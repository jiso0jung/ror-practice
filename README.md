# Ruby on Rails 시작하기
* Rails 7
* ruby 2.7.2
## Part 1
CRUD 구현 <br/>
https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one
#### 오류 내용
* rubymine에서 프로젝트 오픈 시 설정 로드 불가
  * 프로젝트가 read-only 로 생성되었기 때문. `sudo chmod -R 777 프로젝트` 적용
* 테스트 진행 오류
  * rspec 3.5에서 4.0으로 버전업 후 해결
  * https://makandracards.com/makandra/495334-how-to-fix-wrongscopeerror-when-using-rspec_rails-with-rails-6-1
* 테스트 시 support 하위파일 미반영
  * spec_helper.rb에서 `RSpec.configuration` 삭제 및 하위내용 `RSpec.configure`에 통합
* `Faker::StarWars` 상수 초기화 오류
  * 구버전 상수인 듯 보임. `Faker::Movies::StarWars`로 수정

## Part 2
JWT로 유저 토큰기반 인증 <br/>
https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-two

## Part 3
버전관리/직렬화/페이지네이션 <br/>
https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-three
