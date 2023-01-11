<script>
    export let num, type;
</script>

<div id={"citations-" + num}>
    <span class="text-muted">{num}. </span>
    <span class="badge bg-primary">{type}</span>
    <slot/>
</div>