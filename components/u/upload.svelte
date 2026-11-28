<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w-aiud5ru.css';
import '../../css/z/zhm-dib2f.css';
import '../../css/l/l9fprqb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w-aiud5ru"/><path class="zhm-dib2f"/><path class="l9fprqb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:upload" {...props}></Icon>
