<template>
  <subpage :pagetit="'자료실'">
    <div class="referencepage">
      <div class="subpageguide">
        도서와 관련된 추가 자료를 다운로드 할 수 있습니다.
      </div>
    </div>
    <listComm :lists="lists" />
  </subpage>
</template>
<script>
import Subpage from "@/layout/components/Subpage";
import listComm from "@/layout/components/listComm";
export default {
  components: { Subpage, listComm },
  data() {
    return {
      lists: [
        {
          img: "/images/books_image/book01.jpg",
          title: "/Do it! 실습 파일과 학습 파일 내려받기",
          date: "2019.04.15",
          dec: "책을 다 공부한 독자를 위한 실전 프로젝트입니다.<br/>" +
              "웹 사이트에서 자주 사용하는 '이미지 슬라이드 쇼' 프로그램을 만드는 방법을 단계별로 공부할 수 있습니다.",
          link1: "",
          link2: "",
        }
      ]
    }
  }
}
</script>
