<script setup>

import Header from "@/components/page_fourth/Header.vue";
import MemberCard from "@/components/page_fourth/MemberCard.vue";
</script>

<template>
  <div class="Page-fourth page">
    <div class="header">
      <Header />
    </div>
    <div class="team">
      <MemberCard name="First Member" position="Założyciel Crypto Dive" photoUrl="../src/assets/firstMember.png"
        instagramUrl="https://instagram.com/" telegramUrl="https://t.me/" />
      <MemberCard name="Second Member" position="Redaktor i resercher" photoUrl="../src/assets/secondMember.png"
        instagramUrl="https://instagram.com/" telegramUrl="https://t.me/" />
      <MemberCard name="Third Member" position="Content manager" photoUrl="../src/assets/thirdMember.png"
        instagramUrl="https://instagram.com/" telegramUrl="https://t.me/" />
    </div>
  </div>
</template>

<style scoped>
.Page-fourth {
  min-height: 100vh;
}

.team {
  display: flex;
  flex-direction: row;
  gap: 3vw;
  justify-content: space-around;
  align-items: flex-start;
  flex-wrap: wrap;
  margin: 50px 128px 0 128px;
  padding-bottom: 40px;
}
</style>
