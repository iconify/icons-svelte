<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx30rb9t.css';
import '../../css/j/jzm1kkbyl.css';
import '../../css/t/t938dqb3o.css';
import '../../css/j/jej2n1bzn.css';
import '../../css/f/fbkeuub5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="jzm1kkbyl"/><path class="t938dqb3o"/><path class="jej2n1bzn"/><path class="fbkeuub5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:rowing" {...props}></Icon>
