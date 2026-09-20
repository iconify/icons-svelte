<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubyn_s8ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubyn_s8ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-fill" {...props}></Icon>
