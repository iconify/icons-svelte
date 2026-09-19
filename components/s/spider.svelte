<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv78ecc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv78ecc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:spider" {...props}></Icon>
