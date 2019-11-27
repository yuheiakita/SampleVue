<template>
  <div class="admin-new-post-page">
    <section class="new-post-from">
      <AdminPostFrom />
    </section>
  </div>
</template>

<script>
import AdminPostFrom from '@/components/Admin/AdminPostFrom'

export default {
    components: {
        AdminPostFrom,
    }
}
</script>

<style scoped>
.new-post-from {
    width: 90%;
    margin: 20px auto;
}

@media (min-width: 768px) {
    .new-post-from {
        width: 500px;
    }
}
</style>