<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wn_ne-bjp.css';
import '../../css/l/lybdvkb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wn_ne-bjp"/><path class="lybdvkb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:webcam-video-circle-flat" {...props}></Icon>
