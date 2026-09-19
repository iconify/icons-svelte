<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyixm7aak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="iyixm7aak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-moving" {...props}></Icon>
