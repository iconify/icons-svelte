<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huyz1cckc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huyz1cckc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-snowy-heavy" {...props}></Icon>
