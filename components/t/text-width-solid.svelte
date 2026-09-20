<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-9_lojyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j-9_lojyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:text-width-solid" {...props}></Icon>
