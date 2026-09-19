<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6bv4yrfa.css';
import '../../css/p/pkyc0qbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="u6bv4yrfa"/><path class="pkyc0qbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ruby" {...props}></Icon>
