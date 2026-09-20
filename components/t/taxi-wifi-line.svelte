<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy11gn_xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy11gn_xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:taxi-wifi-line" {...props}></Icon>
