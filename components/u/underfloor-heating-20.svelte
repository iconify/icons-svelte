<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzmkpsb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yzmkpsb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underfloor-heating-20" {...props}></Icon>
