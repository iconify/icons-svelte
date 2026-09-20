<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbze9qbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbze9qbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-remove" {...props}></Icon>
