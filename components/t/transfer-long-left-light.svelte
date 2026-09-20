<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrwx__1dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrwx__1dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-long-left-light" {...props}></Icon>
