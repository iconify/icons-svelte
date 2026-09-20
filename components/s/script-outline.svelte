<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj11ntbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj11ntbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:script-outline" {...props}></Icon>
