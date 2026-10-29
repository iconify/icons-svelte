<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ih5ozlbgy.css';
import '../../css/t/tmvc5lbma.css';
import '../../css/c/co407c62o.css';
import '../../css/i/i7g8jgxjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ih5ozlbgy wm-deco"/><path class="tmvc5lbma wm-deco"/><path class="co407c62o wm-deco"/><path class="i7g8jgxjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stethoscope-blueprint" {...props}></Icon>
