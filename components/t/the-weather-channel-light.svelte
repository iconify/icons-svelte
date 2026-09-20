<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2zc8cbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2zc8cbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-weather-channel-light" {...props}></Icon>
