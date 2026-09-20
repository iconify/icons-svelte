<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnp-2vbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnp-2vbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:weather-night" {...props}></Icon>
