<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3t3vqbie.css';
import '../../css/u/uook0dnzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a3t3vqbie"/><path class="uook0dnzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-mask-20-bold" {...props}></Icon>
