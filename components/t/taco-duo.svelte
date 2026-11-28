<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyruocc3c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bm_askbkq.css';
import '../../css/c/cxp113bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyruocc3c secondary"/><g class="dt0cm9dhy primary"><path class="bm_askbkq"/><path class="cxp113bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:taco-duo" {...props}></Icon>
