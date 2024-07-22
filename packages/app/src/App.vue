<script lang="ts" scoped>
import { ref } from "vue";

import {
  Entry,
  type TypeFromVUEFile,
  type TypeFromTSFile,
} from "design-system";

const fromVue = ref<TypeFromVUEFile[]>([]);
fromVue.value.filter((t) => t);

const fromTSFile: TypeFromTSFile[] = [];
fromTSFile.filter((t) => t);
</script>

<template>
  <Entry :type="1"></Entry>
</template>
