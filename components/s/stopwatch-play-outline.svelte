<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8j3ojtso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8j3ojtso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-play-outline" {...props}></Icon>
