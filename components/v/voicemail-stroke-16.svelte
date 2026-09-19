<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/rlix6ub3a.css';
import '../../css/b/bteimacwg.css';
import '../../css/u/u6x4exbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="rlix6ub3a"/><circle class="bteimacwg"/><path class="u6x4exbvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:voicemail-stroke-16" {...props}></Icon>
