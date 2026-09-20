<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryaepbcls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryaepbcls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:treat-outline" {...props}></Icon>
