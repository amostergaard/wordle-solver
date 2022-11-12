<script setup lang="ts">
import { NConfigProvider } from "naive-ui";

import GuessSubmitForm from "./components/GuessSubmitForm.vue";
import LetterRefinementForm from "./components/LetterRefinementForm.vue";
import PossibleWordList from "./components/PossibleWordList.vue";
</script>

<template>
  <n-config-provider>
    <GuessSubmitForm />
    <LetterRefinementForm />
    <PossibleWordList />
  </n-config-provider>
</template>
