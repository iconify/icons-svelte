<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yippcf2ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yippcf2ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shuttlecock" {...props}></Icon>
