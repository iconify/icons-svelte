<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwc-_dbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwc-_dbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:unplug" {...props}></Icon>
