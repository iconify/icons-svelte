<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tlyj1gbrg.css';
import '../../css/h/hbgghxbas.css';
import '../../css/p/pfta3sbaz.css';
import '../../css/x/xf7v9-bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tlyj1gbrg"/><path class="hbgghxbas"/><path class="pfta3sbaz"/><path class="xf7v9-bsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-bold-duotone" {...props}></Icon>
