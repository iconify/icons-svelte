<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3f9kr8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ds3f9kr8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:web-browser-screen" {...props}></Icon>
