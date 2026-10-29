<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/iv6i0wvsu.css';
import '../../css/q/qfd-q7blm.css';
import '../../css/k/k2m212bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="iv6i0wvsu"/><path class="qfd-q7blm wm-a"/><path class="k2m212bgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-half-duo" {...props}></Icon>
