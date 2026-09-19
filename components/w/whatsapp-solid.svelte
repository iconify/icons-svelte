<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zpd_gbb0e.css';
import '../../css/g/gmvxbacpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zpd_gbb0e"/><path class="gmvxbacpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:whatsapp-solid" {...props}></Icon>
