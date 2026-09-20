<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stun2duqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="stun2duqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wlan-free" {...props}></Icon>
