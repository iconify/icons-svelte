<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua0op0ati.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ua0op0ati"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stratovolcano-smoke-2" {...props}></Icon>
