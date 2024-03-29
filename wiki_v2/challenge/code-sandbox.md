---
title: CodeSandbox 사용방법
category: 챌린지 사용 방법
order: 3
---

## CodeSandbox 사용방법

### 로그인

- 우선 [https://codesandbox.io/](https://codesandbox.io/) 이동해서. 회원가입 및 로그인을 하세요. 
- 그 다음. 숙제 제출용으로 생성된 템플릿 "Today's Blueprint" 를 클릭하여 이동합니다. 
- 해당 템플릿은 챌린지 과제 페이지의 우측 상단에서 발견하실 수 있습니다. 아래 캡쳐 이미지를 참고하세요.
  > ![Imgur](https://i.ibb.co/QXGfK9H/o06t6SJ.png)

### 제출 방법

- 템플릿 위에 그대로 코딩을 합니다.
- 코딩을 완료한 후, 좌측 상단에 **file > save**(혹은 커맨드/ctrl+S)를 눌러서 저장합니다.
  > ![Imgur](https://i.ibb.co/NYXJwYs/0.png)
- 혹은! 우측 상단에 **fork** 를 클릭해도 됩니다.
- 저장하는 순간! 링크가 자동으로 새롭게 생성됩니다! 브라우저 주소창에 있는 그 링크를 복사합니다.
  > ![](https://i.ibb.co/KVhPV03/Screen-Shot-2021-07-01-at-4-17-41-PM.png)
- 해당 링크를 챌린지 웹사이트에서 제출하면 끝!

### 정상적으로 제출되었나요?

- 정상적으로 제출되었다면. 아래와 같이 저장되었다는 문구가 뜨며, 확인 이메일이 옵니다.
- 확인 이메일이 오지 않으면. 정상 제출된 것이 아니므로. 유의하시기 바랍니다.
- 마감 시간 (새벽 6시)까지 해당 링크를 계속 변경. 업데이트 할 수 있습니다.
  > ![Imgur](https://i.ibb.co/LPD4Qhb/fHxZSau.png)

### 링크 제출 시 유의사항

- .io 로 끝나는 링크로 보내주시면 코드를 볼 수 없습니다!
> - (좋은 예시) [https://codesandbox.io/s/kw0x07o955](https://codesandbox.io/s/kw0x07o955)
> - 잘못된 예시) [https://213vk4vl6j.codesandbox.io/](https://213vk4vl6j.codesandbox.io/)
- 코딩챌린지 정답은 그 다음날 챌린지 웹사이트를 통해 알려드립니다.
- 정상적으로 제출되었다면 제출 확인 이메일이 옵니다. **이메일이 안 왔다면, 정상 제출이 안 된 것이니 제출 확인 이메일이 왔는지 꼭! 체크** 해주세요!
- 매번 챌린지가 바뀔 때마다, **매번 새로운 샌드박스를 생성하셔서 제출**하셔야 합니다. 제출하는 링크가 매번 달라야 합니다!
- **저장을 확실히 한 후 제출**하시기 바랍니다! 저장 안 하시고 빈 화면 제출하시는 분들이 은근 많습니다! 저장 확실히 때리고 **크롬 시크릿 화면에서 링크 확인한 다음에 제출**하세요!
- **해당 링크를 다시 클릭해보셔서 제대로 제출이 되었는지도 확인**하시기 바랍니다. 간혹, 텅 빈 링크를 잘못 보내셔서 졸업 못 하시는 분들이 있습니다! 꼭~ 더블 체크해 주세요.
- **제출 확인 이메일이 오지 않고, 정상 제출이 되지 않는다면?** help@nomadcoders.co 로 아래 내용을 적어서 이메일 보내주세요.
> - 계정 이메일
> - 참여하는 챌린지 명
> - 과제# 혹은 Day#
> - 과제 링크 URL
> - 발생하는 에러 내용 설명 및 전체화면 스크린샷

### 코드샌드박스가 너무 느려요. 자꾸 에러나요. 으아악

- 해당 코드샌드박스를 Zip 파일로 엑스포트 합니다. **File > Export to Zip**
- Zip을 열고, 해당 폴더를 VSCode 에서 열고,
- Run "npm install" to install the package.json
- 챌린지를 로컬 컴퓨터에서 차근차근히 합니다.
> - 해당 코드를 복사-붙여넣기 (컴퓨터 ->웹 코드샌드박스로) 합니다.
> - 여전히 샌드박스에서 에러가 나면. 무시하세요.
> - VSC에서 정상 작동했다면. 그냥 그 코드 복-붙하고.
> - 저장하신 후. 생성된 링크를 제출하시면 됩니다.

### VSC 에서는 정상 작동 하다가, CodeSandbox에 복사-붙여넣기 하니 제대로 출력 안 될 때

- 괜찮습니다. 걱정안하셔도 되어요!
- VSC에서 정상 작동하는거 확인하셨다면, 일단 붙여넣기 해서 보내주셔도 좋습니다.

### CodeSandbox가 왜인지 모르지만 잘 작동 안 될 때!

- 좌측 server control panel에서 서버 혹은 샌드박스 재시작(restart) 하시면 됩니다.
  > ![Imgur](https://i.ibb.co/rMjZStz/111.png)

### 그 외 샌드박스 에러 발생 시

- 항상 깃허브 로그인을 하세요~!
- You reached the limit of server sandboxes: 무료로 사용할 때 최대 15개까지입니다. 필요 없는 샌박들을 삭제해보세요.
- 저장 오류: restart server 하세요.
- 502 bad Gateway: 켜놓고 있다가 다른 브라우저가 열렸거나 했을 때 그런 에러가 잘 나는 거 같아요. 샌드박스 안에서 Browser() 있는 거 다 닫아버리고 서버 재시작하고 난 뒤 package.json같은데서 저장 한번 다시 하면 팝업창 뜨면서 에러 안 나는 새로운 브라우저 열릴 겁니다.
- Container Error: 샌드박스 완전히 끄고 조금만 기다렸다가 다시 접속해보시면 정상적으로 작동됩니다.

### 코딩 챌린지 결격 기준

- 나중에 집계할 때 결과가 아래와 같을 경우, 자동 결격 처리됩니다.
> - 제출한 내용이 텅 비어있거나,
> - 최소 조건을 이행하지 못한 경우,
> - 누군가의 코드를 무작정 베낀 것으로 추정된 경우입니다.

### 졸업 타임라인

- D-Day. 챌린지 2주 혹은 6주 진행 끝.
- D+7. 최종 졸업생 확정. Dashboard에 자동으로 쿠폰 발급.

### 코드 챌린지 과제를 유출하지 말아주세요!

- 간혹 개인 블로그 등에 과제 및 솔루션을 공유하시는 분들이 계십니다.
- 챌린지의 묘미를 위하여, 해당 과제 내용 및 솔루션을 유출하지 말아 주세요!
