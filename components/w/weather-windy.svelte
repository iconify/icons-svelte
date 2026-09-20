<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5g_-gyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap5g_-gyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:weather-windy" {...props}></Icon>
