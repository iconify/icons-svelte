<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dpfi26pss.css';
import '../../css/o/oip2tteqt.css';
import '../../css/c/czuzz3bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dpfi26pss"/><path class="oip2tteqt"/><path class="czuzz3bda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-lib-duotone" {...props}></Icon>
