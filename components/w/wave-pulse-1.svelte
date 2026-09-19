<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeu84ubtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeu84ubtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:wave-pulse-1" {...props}></Icon>
