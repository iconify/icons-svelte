<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tybcrmi-m.css';
import '../../css/b/bsvdiixhm.css';
import '../../css/r/r_9lwu93i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="tybcrmi-m"><path class="bsvdiixhm"/><path class="r_9lwu93i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stylus" {...props}></Icon>
