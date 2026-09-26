<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ar0kiqktv.css';
import '../../css/w/w8hsb3bsa.css';
import '../../css/y/ybtsdob7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ar0kiqktv"/><path class="w8hsb3bsa"/><path class="ybtsdob7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-off-bold-duotone" {...props}></Icon>
