<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muky7dbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="muky7dbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stratovolcano-smoke" {...props}></Icon>
