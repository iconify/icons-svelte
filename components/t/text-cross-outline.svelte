<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p14up0_ne.css';
import '../../css/t/tj9p9h5bc.css';
import '../../css/u/uxdowbokt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p14up0_ne"/><path class="tj9p9h5bc"/><path class="uxdowbokt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-outline" {...props}></Icon>
