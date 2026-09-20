<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si8v7jbgr.css';
import '../../css/g/gtawe4d4l.css';
import '../../css/e/e5clwxbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="si8v7jbgr"/><path class="gtawe4d4l"/><path class="e5clwxbmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-bold" {...props}></Icon>
