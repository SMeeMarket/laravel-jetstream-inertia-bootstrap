<template>
    <div class="bg-warning">
        <Link :href="route('testOne')" class="btn btn-danger">to One</Link>
        <h1 class="text-secondary">Test Two Component</h1>
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
