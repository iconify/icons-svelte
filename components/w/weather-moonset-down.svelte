<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v50fc2bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v50fc2bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-moonset-down" {...props}></Icon>
