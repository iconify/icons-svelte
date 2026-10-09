<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyf71qdqm.css';
import '../../css/l/lrc8v1bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eyf71qdqm"/><path class="lrc8v1bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:truck-20-bold" {...props}></Icon>
