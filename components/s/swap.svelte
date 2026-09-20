<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd6pioblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pd6pioblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:swap" {...props}></Icon>
