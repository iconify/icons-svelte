<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q05er5bdz.css';
import '../../css/f/flfh2ebhi.css';
import '../../css/c/c4ir34j_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q05er5bdz"/><path class="flfh2ebhi"/><path class="c4ir34j_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tags" {...props}></Icon>
