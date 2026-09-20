<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2p6bwb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2p6bwb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-dust" {...props}></Icon>
