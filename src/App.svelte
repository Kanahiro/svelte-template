<script lang="ts">
    import { Router, Route } from 'svelte-routing';
    import Index from './routes/Index.svelte';
</script>

<Router>
    <Route path="/" component={Index} />
</Router>
