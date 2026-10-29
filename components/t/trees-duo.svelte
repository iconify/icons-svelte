<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/slc86ootb.css';
import '../../css/h/hqlqb8bfm.css';
import '../../css/b/bou945bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="slc86ootb"/><path class="hqlqb8bfm wm-a"/><path class="bou945bat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trees-duo" {...props}></Icon>
