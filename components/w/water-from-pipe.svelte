<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au8ux7_ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="au8ux7_ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:water-from-pipe" {...props}></Icon>
