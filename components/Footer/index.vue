<footer class="bg-green-600 text-white py-6 mt-12">
    <div class="max-w-7xl mx-auto px-4 text-center">
      <p>&copy; 2025 Green Allegro. Wszystkie prawa zastrzeżone.</p>
    </div>
  </footer>

<script setup>
import { ref } from "vue";

useHead({
    bodyAttrs: {
        class: "bg-green-50 text-gray-800 font-sans",
    },
});

const isMenuOpen = ref(false);
const toggleMenu = () => {
    isMenuOpen.value = !isMenuOpen.value;
};
</script>
