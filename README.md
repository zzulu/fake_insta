### 1. CRUD 끝내기 (non scaffold)

**RESTful** 하게 짜기! (posts 컨트롤러, post 모델!)

RESTful이란, 주소창(url)을 통해서 자원(리소스)과 행위(HTTP Verb)를 표현하는 것.

[가장 깔끔한 설명](http://meetup.toast.com/posts/92)

[routes](#1. routes.rb)

#### 0. 기본 사항

 - `git` 셋팅(git init부터)
 - C/R/U/D 마다 **commit** 하기
 - `posts` 컨트롤러와 `post` 모델만!

# 1. routes.rb

```ruby
  # index
  get '/posts' =>
  # Create
  get '/posts/new' =>
  post '/posts'=>
  # Read
  get '/posts/:id' =>
  # Update
  get '/posts/:id/edit' =>
  put '/posts/:id' =>
  # Delete
  delete '/posts/:id' =>
```

### 2. scaffolding.. 편하게 CRUD

### 3. 파일업로드(내일..? 넘어갈수도..)

  `gem carrierwave`

### 3-1. 사진 크기 조절하여 저장

  `gem mini_magick`

### 4. 인스타처럼 꾸미기(카드형 배치)
