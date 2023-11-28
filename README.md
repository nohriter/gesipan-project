Spring Project

<details>
<summary>요구사항</summary>

## 요구사항

### 회원

- 회원은 소셜로그인을 통해 회원가입을 할 수 있다.
    - 회원은 이메일로 가입한다.
    - 닉네임을 설정할 수 있다.

### 게시글

- 제목을 작성할 수 있다.
- 내용을 작성할 수 있다.
- 아이템 이미지를 첨부할 수 있다.
- 카테고리를 설정할 수 있다.
- 경매 마감시간을 설정할 수 있다. (3일, 7일)
    - 분단위로 측정
    - 경매가 시작된 즉시 타이머가 돈다.
- 경매 시작가를 설정할 수 있다.
    - 투찰 시 경매 시작가보다 낮게 신청 할 수 없다.
    - 경매 최소입찰가 초과금액이 투찰될 경우 최저금액이 변경된다.
- 경매 상한가를 설정할 수 있다.
    - 경매 상한가에 일치하는 투찰이 생기면 그즉시 경매는 종료되고 매칭된다.
- 입찰 단위를 설정할 수 있다. (100원, 1000원, 5000원, 1만원, 10만원)
    - 입찰단위는 상한가보다 높게 설정할 수 없다.
- 상품을 최초 등록하면 경매시간 등 주요정보를 변경할 수 없다.
    - 경매시간, 시작가, 상한가
- 입찰자 수가 0명인 경우에 작성글은 삭제가 가능, 1명 이상인경우 삭제 불가
- 게시글에는 댓글을 달 수 있다.
- 게시글에는 조회수가 존재한다.
- 게시글에는 좋아요 기능이 존재한다.
- 게시글에는 거래 상태가 존재한다.
    - 거래전, 거래중, 거래완료
- 투찰이 발생하면 글 작성자에게 알림을 전송한다.
- 댓글이 달리면 글 작성자에게 알림을 전송한다.

### 댓글

- 게시글에는 댓글을 달 수 있다.
- 댓글에 댓글을 달 수 있다.

### 알림

- 알림을 모아볼 수 있다.
- 알림의 확인여부를 체크할 수 있다.

</details>
