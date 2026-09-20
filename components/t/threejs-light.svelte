<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pvl2anbys.css';
import '../../css/v/vagq61bug.css';
import '../../css/r/rj2_rc7to.css';
import '../../css/w/wa9awwb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="pvl2anbys"/><path clip-rule="evenodd" class="vagq61bug"/><path clip-rule="evenodd" class="rj2_rc7to"/><path clip-rule="evenodd" class="wa9awwb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:threejs-light" {...props}></Icon>
