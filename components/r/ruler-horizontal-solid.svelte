<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9incsb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9incsb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ruler-horizontal-solid" {...props}></Icon>
