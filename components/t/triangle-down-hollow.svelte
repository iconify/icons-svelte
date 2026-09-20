<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkp1ythty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rkp1ythty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:triangle-down-hollow" {...props}></Icon>
