<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx0rv7bbf.css';
import '../../css/k/khdf871ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xx0rv7bbf"/><path class="khdf871ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-off-20-bold" {...props}></Icon>
