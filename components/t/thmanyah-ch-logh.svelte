<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8n54_i3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8n54_i3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:thmanyah-ch-logh" {...props}></Icon>
