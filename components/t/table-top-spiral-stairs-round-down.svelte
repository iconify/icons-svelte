<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epjs85bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="epjs85bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-spiral-stairs-round-down" {...props}></Icon>
