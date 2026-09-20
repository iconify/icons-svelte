<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbbxgnbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbbxgnbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-weather-channel-dark" {...props}></Icon>
