<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu2r8si_d.css';
import '../../css/u/unsvoio8e.css';
import '../../css/w/w7y0ng4cv.css';
import '../../css/i/ik07y_b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="yu2r8si_d"/><path class="unsvoio8e"/><path class="w7y0ng4cv"/><path class="ik07y_b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:soup-can" {...props}></Icon>
