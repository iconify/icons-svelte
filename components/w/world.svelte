<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-l217ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ld-l217ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:world" {...props}></Icon>
