미니 블로그 기획하기

필요한 기능
- 글목록 보기(리스트형태)
- 글 보기 기능
- 댓글 보기 기능
- 글 작성 기능
- 댓글 작성 기능

글 작성 화면    <-클릭      메인화면       클릭->        글 보기 화면 
제목입력                        글 작성 버튼             글 제목   
내용 입력                       글 작성 버튼              글 내용
내용 입력                       글                        댓글
                                                          댓글 내용 입력
글작성 완료 버튼                                            댓글 작성 완료 버튼


npx create-react-app mini-blog

필요한 패키지
react-router-dom(v6): 리액트 앱에서 페이지 전환을 위해 사용
styled=components(v5): 스타일링을 위한 컴포넌트

npm install --save react-router-dom styled-components



주요 컴포넌트 구성하기
- 글 목록 보기 기능: PostList 컴포넌트 PostListItem 컴포넌트
- 글 보기 기능: Post 컴포넌트
- 댓글 목록 보여주기: CommentList 컴포넌트, CommentListItem 컴포넌트
- 댓글 작성하기: CommentWrite 컴포넌트
- 글 작성 기능: PostWrite 컴포넌트

폴더 구성하기
src
- component
	- list: 리스트와 관련된 컴포넌트를 모아놓은 폴더, - page: 페이지 컴포넌트들을 모아놓은 폴더, - ui: UI컴포넌트들을 모아놓은 폴더


프로젝트 설계할 때에는 top-down  방식으로 큰 그림을 먼저 그리고 그리고 작은 부분을 구체화 시켜 나간다
프로젝트를 구현할 때에는 반대로 bottom-up 방식으로 작은 부분부터 구현한 후에 작은 부분들을 모아 큰 부분을 완성하게합니다.

UI 컴포넌트
- Button 컴포넌트
- TextInput 컴포넌트


남들 30분이면 만드는걸 난 3시간 걸리네 ..
