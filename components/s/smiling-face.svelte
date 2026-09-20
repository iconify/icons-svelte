<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/e/ecrffp_lt.css';
import '../../css/q/qmnpc1bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="ij2x_72vy"><path class="ecrffp_lt"/><circle class="qmnpc1bre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:smiling-face" {...props}></Icon>
