<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh2-3_b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bh2-3_b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:transit-vehicle-on-railway-track" {...props}></Icon>
