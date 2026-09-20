<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfj2ffzpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfj2ffzpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:search" {...props}></Icon>
