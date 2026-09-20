<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v2rqs8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9v2rqs8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-tick-outline" {...props}></Icon>
