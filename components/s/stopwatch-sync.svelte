<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tafbgqbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tafbgqbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-sync" {...props}></Icon>
