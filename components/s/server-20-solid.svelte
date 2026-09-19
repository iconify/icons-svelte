<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gfuhj1bvk.css';
import '../../css/c/cmlgwxbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="gfuhj1bvk"/><path clip-rule="evenodd" class="cmlgwxbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:server-20-solid" {...props}></Icon>
