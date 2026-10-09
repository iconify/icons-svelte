<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e471qky_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e471qky_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-20-bold" {...props}></Icon>
