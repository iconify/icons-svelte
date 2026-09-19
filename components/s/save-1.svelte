<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oc7xiubde.css';
import '../../css/m/m51gvsb7x.css';
import '../../css/z/z13-pabfj.css';
import '../../css/k/k65lz2a_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="oc7xiubde"/><path class="m51gvsb7x"/><path class="z13-pabfj"/><path class="k65lz2a_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:save-1" {...props}></Icon>
