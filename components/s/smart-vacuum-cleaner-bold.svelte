<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c07eu3b7m.css';
import '../../css/u/u7e-2iblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c07eu3b7m"/><path clip-rule="evenodd" class="u7e-2iblc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-vacuum-cleaner-bold" {...props}></Icon>
