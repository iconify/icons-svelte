<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/px-v8fp6s.css';
import '../../css/l/l_ox2fgog.css';
import '../../css/x/xs3lbmb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="px-v8fp6s"/><path class="l_ox2fgog"/><path class="xs3lbmb9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-bolt-bold" {...props}></Icon>
