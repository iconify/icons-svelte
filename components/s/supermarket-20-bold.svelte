<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7xnc1b0i.css';
import '../../css/u/ucg2xpeqq.css';
import '../../css/l/l7hzbkbbx.css';
import '../../css/m/mw2wz86ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m7xnc1b0i"/><path class="ucg2xpeqq"/><path class="l7hzbkbbx"/><path class="mw2wz86ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supermarket-20-bold" {...props}></Icon>
