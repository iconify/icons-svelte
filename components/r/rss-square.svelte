<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7f0m03tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a7f0m03tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:rss-square" {...props}></Icon>
