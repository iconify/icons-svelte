<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmz1t60mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmz1t60mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:thumbs-up" {...props}></Icon>
