<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l49z6bbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l49z6bbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray-remove" {...props}></Icon>
