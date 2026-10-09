<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc7985b_u.css';
import '../../css/v/v3ruwkbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cc7985b_u"/><path class="v3ruwkbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scope-3-20-bold" {...props}></Icon>
