<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpcu2565j.css';
import '../../css/r/rs94qeblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cpcu2565j"/><path class="rs94qeblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stickies" {...props}></Icon>
