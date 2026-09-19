<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zqbpy6boz.css';
import '../../css/z/zuoznrbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="zqbpy6boz"/><path class="zuoznrbss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:slider-round-1" {...props}></Icon>
