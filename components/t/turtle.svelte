<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r3n5yaczg.css';
import '../../css/j/j3_h7f7oi.css';
import '../../css/t/ty867pbrf.css';
import '../../css/p/pstgohcda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r3n5yaczg"/><path class="j3_h7f7oi"/><path class="ty867pbrf"/><path class="pstgohcda wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:turtle" {...props}></Icon>
