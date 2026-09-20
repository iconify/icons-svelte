<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvx14oi-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvx14oi-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray" {...props}></Icon>
