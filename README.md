# http 완벽가이드 스터디

- 2장: 2019.9.2 ~ 10.27 (7주)
- 1장: 2019.8.1 ~ 8.26 (4주)

---

### ING

[7장-2](./chapter_7-2/README.md)

---

## 사전 읽어보시는 글

1. 글은 해당 chapter 폴더의 README파일의 본인 이름 옆에 link해주시면됩니다.
2. 블로그로 작성하신 분들은 블로그 link, 마크다운으로 올리신 분은 마크다운 파일첨부하시고, 해당 파일 link
3. master에서 바로 작성하지 마시고, 서로 피드백을 위해서 branch 생성하여 pr로 올려주세요. (branch 이름 규칙은 아래 2번)

### 컨벤션

#### 파일 관리

1. 마크다운 파일은 `chap1_김나영.md`으로 생성해주세요.
2. 아래 정리글 링크에서는 해당 글 옆에 `- 글제목`로 작성해주세요
   > 예: 1. 김나영 - [글 제목](https://feel5ny.github.io/2019/07/07/Joylog_003/)
3. ☀️ 마크다운으로 올려주시는 분들 중 최종본이 마크다운이실 경우, 해당 폴더 경로로 링크부탁드립니다 :)
   > 예: 1. 김나영 - [글제목](/chapter_2/README.md)
4. 마크다운에 포함된 asset들은 폴더를 생성해서 해당 폴더에 옮기신 후, 마크다운에 링크해주세요.
   > 폴더 이름은 `src_김나영` 이렇게 지어주세요.
5. 공유이미지 사용은 [아래](#shared_images)를 확인해주세요

#### PR

1. PR 올리실때 브랜치 생성은 master에서 `chap1_김나영`으로 생성해주세요.
   - PR 생성 후에는 몇번째 챕터 관련한 pr인지 label을 붙여주세요!
     > 여러가지 챕터 pr이 산발적으로 올라오는 것을 정리하기위해 라벨링합니다.
2. PR 올리실때 제목은 `[bookCrush/httpPerfectGuide] chap1_김나영` 으로 생성해주세요.

   > 개인이 갖고 있는 다른 repo의 PR과 혼란을 막기위해 prefix를 붙입니다.

<a name="shared_images"></a>

### 공유 이미지

- http글과 관련된 이미지들중 공유할만한 이미지들은 `/images`에 올려주시면됩니다.
  > 원서 이미지도 순차적으로 업로드가 진행되고 있습니다.
  > 원서 이미지 업로드 컨벤션: `Figures A-B. description` --> `A-B.png`
- 파일명은 chapter1관련 이미지의 경우 `1-1.jpg`형식으로 되어있습니다. 마지막 숫자의 다음숫자로 명명하여서 올려주세요.
  > 마지막 파일이 `1-1.jpg`라면, `1-2.jpg`로 올리기
- 올려주실때는 pr로 올려주시면 바로 승인하겠습니다.
  > pr 제목: `[bookCrush/httpPerfectGuide] chap1_공용이미지 추가`
