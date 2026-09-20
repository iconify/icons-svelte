<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckgc0n10h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ckgc0n10h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:spa" {...props}></Icon>
