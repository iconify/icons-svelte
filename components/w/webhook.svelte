<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnh16m-tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnh16m-tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:webhook" {...props}></Icon>
