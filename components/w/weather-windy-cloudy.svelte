<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqab-ccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqab-ccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:weather-windy-cloudy" {...props}></Icon>
