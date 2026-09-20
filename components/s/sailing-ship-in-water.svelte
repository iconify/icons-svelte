<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsiosqx3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bsiosqx3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sailing-ship-in-water" {...props}></Icon>
