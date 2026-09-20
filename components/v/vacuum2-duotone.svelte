<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/ffiiy4qkf.css';
import '../../css/c/c0_inmbrs.css';
import '../../css/m/m5_rub7qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ffiiy4qkf"/><path class="c0_inmbrs"/><path clip-rule="evenodd" class="m5_rub7qo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:vacuum2-duotone" {...props}></Icon>
