<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xezhn6bls.css';
import '../../css/o/oxb1cbk0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="xezhn6bls"/><path class="oxb1cbk0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-centroid" {...props}></Icon>
