<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xz-zwdqsc.css';
import '../../css/n/n9_gztbdw.css';
import '../../css/i/i-5ejf2qe.css';
import '../../css/y/yj742hgsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xz-zwdqsc"/><path class="n9_gztbdw"/><path class="i-5ejf2qe"/><path class="yj742hgsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:shopping-cart" {...props}></Icon>
