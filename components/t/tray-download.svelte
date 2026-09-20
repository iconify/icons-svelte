<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccrrbfbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccrrbfbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray-download" {...props}></Icon>
