<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mt6ba2bga.css';
import '../../css/t/t-5vfcbmo.css';
import '../../css/i/ihsle8fcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mt6ba2bga"/><path class="t-5vfcbmo"/><path class="ihsle8fcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget-add-duotone" {...props}></Icon>
