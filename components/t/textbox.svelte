<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv4_7tbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv4_7tbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:textbox" {...props}></Icon>
