<template>
    <div>
        <p>product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur quidem iste soluta expedita molestias voluptates beatae voluptatem odit fugit eum illum, blanditiis repellat aperiam. Nobis consequatur obcaecati ea laudantium numquam?</p>
    </div>
</template>

<script>
    const { id } = useRoute().params.id
</script>

<style scoped>

</style>