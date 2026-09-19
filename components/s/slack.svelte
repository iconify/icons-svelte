<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj9alb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="erj9alb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:slack" {...props}></Icon>
