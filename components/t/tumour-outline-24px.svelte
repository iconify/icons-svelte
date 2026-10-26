<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rh1136bzs.css';
import '../../css/u/ud-z92y1b.css';
import '../../css/d/d0o4gmbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rh1136bzs"/><path clip-rule="evenodd" class="ud-z92y1b"/><path class="d0o4gmbsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:tumour-outline-24px" {...props}></Icon>
