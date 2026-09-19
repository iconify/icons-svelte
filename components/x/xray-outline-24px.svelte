<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qwrl_0bad.css';
import '../../css/i/iuu1x3ifx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qwrl_0bad"/><path clip-rule="evenodd" class="iuu1x3ifx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:xray-outline-24px" {...props}></Icon>
