<template>
<div class="admin-post-page">
    <section class="update-from">
        <AdminPostFrom :post="loadedPost"/>
    </section>
    </div>
</template>

<script>
import AdminPostFrom from '@/components/Admin/AdminPostFrom'
export default {
    layout: 'admin',
    components: {
        AdminPostFrom
    },
    data() {
        return {
            loadedPost: {
                author: 'Maximilian',
                title: 'My awesome Post',
                content: 'Super amazing, thanks for that!',
            }
        }
    }
}
</script>