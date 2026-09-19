<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/omzavhb5d.css';
import '../../css/c/ckfucqbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="omzavhb5d"/><path clip-rule="evenodd" class="ckfucqbjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:server-stack-20-solid" {...props}></Icon>
