<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mb_m1r3fi.css';
import '../../css/v/vdylksbhi.css';
import '../../css/j/j9dgfb5fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mb_m1r3fi"/><path class="vdylksbhi"/><path clip-rule="evenodd" class="j9dgfb5fm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tuning-square-bold" {...props}></Icon>
