<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su8_q7bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="su8_q7bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:square-outline" {...props}></Icon>
