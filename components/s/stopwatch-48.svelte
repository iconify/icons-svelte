<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7474gbcq.css';
import '../../css/f/fk4kw9brn.css';
import '../../css/k/knmmfib1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w7474gbcq"/><path class="fk4kw9brn"/><path class="knmmfib1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stopwatch-48" {...props}></Icon>
