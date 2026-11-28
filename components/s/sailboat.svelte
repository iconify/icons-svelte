<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xs3efil7b.css';
import '../../css/m/mmizfzbwi.css';
import '../../css/w/we9upfblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xs3efil7b"/><path class="mmizfzbwi"/><path class="we9upfblt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sailboat" {...props}></Icon>
