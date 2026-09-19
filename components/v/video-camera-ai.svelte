<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pzh2xemmy.css';
import '../../css/j/jlk5hjb9z.css';
import '../../css/r/rbrzdibek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pzh2xemmy"/><path class="jlk5hjb9z"/><path class="rbrzdibek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:video-camera-ai" {...props}></Icon>
