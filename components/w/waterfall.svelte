<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m45j_9b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m45j_9b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:waterfall" {...props}></Icon>
