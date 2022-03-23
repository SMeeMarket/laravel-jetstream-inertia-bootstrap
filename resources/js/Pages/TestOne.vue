<template>
    <div class="bg-info">
        <Link href="test-one" class="btn btn-danger">to Two</Link>
        <h1 class="text-primary">Test One Component</h1>
    </div>
</template>
<script>
import { Link } from '@inertiajs/inertia-vue3'
export default {
    components:{
        Link
    }
}
</script>
