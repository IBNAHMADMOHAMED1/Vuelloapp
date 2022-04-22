<script setup>
import Button from '@/components/base/Button.vue'
import CloseIcon from '@/components/icons/CloseIcon.vue'

const props = defineProps({
  value: {
    type: Boolean,
    required: true,
    default: false,
  },
})
const emits = defineEmits(['close'])

const modalAction = () => {
  emits('close')
}
</script>



<style>

</style>
