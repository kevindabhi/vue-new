<script setup>
import q from "./data/quizes.json"
import { ref, watch } from "vue";

const quiz =ref(q)
const search = ref("")
</script>