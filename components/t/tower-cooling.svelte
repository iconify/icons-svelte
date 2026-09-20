<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwgmocc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vwgmocc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tower-cooling" {...props}></Icon>
