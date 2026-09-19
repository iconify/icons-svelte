<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q1rgjueje.css';
import '../../css/g/gdumllbcd.css';
import '../../css/o/oi_e6acli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q1rgjueje"/><path clip-rule="evenodd" class="gdumllbcd"/><path class="oi_e6acli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-xmark-solid" {...props}></Icon>
