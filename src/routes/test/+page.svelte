<script lang="js">
    let width;
    let height;
</script>

Paragraph width: {width}px Paragraph height: {height}px

<p bind:clientWidth={width} bind:clientHeight={height}>
    This is some example text.
</p>
