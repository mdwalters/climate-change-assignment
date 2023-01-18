<!-- Think of this as a container  -->

<script>
    export let id;
</script>

<section class="m-3 rounded bg-light p-3 text-dark" id={id}>
    <slot/>
</section>