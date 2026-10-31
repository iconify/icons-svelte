<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfwr5wbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfwr5wbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-plus-corner-round" {...props}></Icon>
