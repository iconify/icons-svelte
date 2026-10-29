<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4-q3o-8g.css';
import '../../css/f/fr8h0cc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wm-k z4-q3o-8g"/><path class="fr8h0cc5s wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-off-solid" {...props}></Icon>
