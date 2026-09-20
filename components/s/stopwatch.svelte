<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw8_6e7bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw8_6e7bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch" {...props}></Icon>
