<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peu1myr5j.css';
import '../../css/i/injsvdbgs.css';
import '../../css/j/j39cvqb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="peu1myr5j"/><path class="injsvdbgs"/><path class="j39cvqb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stopwatch-20-bold" {...props}></Icon>
