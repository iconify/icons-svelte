<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqi81zisr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqi81zisr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-hail" {...props}></Icon>
