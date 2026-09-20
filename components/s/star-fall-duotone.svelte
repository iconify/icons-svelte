<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iacwmfb0y.css';
import '../../css/f/fb7w0qbrc.css';
import '../../css/r/rxs9aqbon.css';
import '../../css/b/brt5hcczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iacwmfb0y"/><path class="fb7w0qbrc"/><path class="rxs9aqbon"/><path class="brt5hcczb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-fall-duotone" {...props}></Icon>
