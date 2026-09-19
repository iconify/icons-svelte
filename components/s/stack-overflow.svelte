<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqhu8rbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":336,"height":432};
const content = `<path class="uqhu8rbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:stack-overflow" {...props}></Icon>
