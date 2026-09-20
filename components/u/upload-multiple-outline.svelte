<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz1_7bcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz1_7bcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-multiple-outline" {...props}></Icon>
