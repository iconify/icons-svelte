<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkszstbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkszstbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-music-outline" {...props}></Icon>
