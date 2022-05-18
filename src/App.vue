<template>
  <recruitment-survey></recruitment-survey>
  <user-experiences></user-experiences>
</template>

<script>
import RecruitmentSurvey from './components/survey/RecruitmentSurvey.vue';
import UserExperiences from './components/survey/UserExperiences.vue';

export default {
  components: {
    RecruitmentSurvey,
    UserExperiences,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
}
</style>
