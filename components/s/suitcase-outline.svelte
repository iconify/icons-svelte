<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d7wynpbjw.css';
import '../../css/p/pxwqqeb5y.css';
import '../../css/l/lssgj34zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d7wynpbjw"/><path class="pxwqqeb5y"/><path class="lssgj34zs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-outline" {...props}></Icon>
