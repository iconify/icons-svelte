<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo9q2tsch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="xo9q2tsch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:windows" {...props}></Icon>
