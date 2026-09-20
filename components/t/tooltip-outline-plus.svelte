<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfg20eb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfg20eb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-outline-plus" {...props}></Icon>
