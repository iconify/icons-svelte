<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa1_sbb_c.css';
import '../../css/c/c4dmikbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fa1_sbb_c"/><path class="c4dmikbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-vertical-ellipse" {...props}></Icon>
