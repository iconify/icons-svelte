<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhxvgwbwc.css';
import '../../css/r/rs26g1b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhxvgwbwc"/><path class="rs26g1b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:tornado" {...props}></Icon>
