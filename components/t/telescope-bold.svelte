<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0iwjtb9z.css';
import '../../css/w/wvdj1rwub.css';
import '../../css/n/nahr265oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0iwjtb9z"/><path class="wvdj1rwub"/><path class="nahr265oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:telescope-bold" {...props}></Icon>
