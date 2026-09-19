<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtemydjmd.css';
import '../../css/t/to-5kdesz.css';
import '../../css/k/kuim36bpx.css';
import '../../css/g/gvkoecj5g.css';
import '../../css/h/hsixsabso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVGUJ7Mq8OH" width="28" height="25" x="2" y="4" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="dtemydjmd"/></mask><g class="to-5kdesz"><path class="kuim36bpx"/><g mask="url(#SVGUJ7Mq8OH)" class="gvkoecj5g"><path class="hsixsabso"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:yellow-heart" {...props}></Icon>
