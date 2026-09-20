<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yic6p8mfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yic6p8mfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:star-solid-expressive" {...props}></Icon>
