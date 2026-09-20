<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjd08npta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjd08npta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-sunny-off" {...props}></Icon>
