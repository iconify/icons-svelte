<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrme0_b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrme0_b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tablecheck" {...props}></Icon>
