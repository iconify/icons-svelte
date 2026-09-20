<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vvp3mvl2g.css';
import '../../css/z/zbfibgbbq.css';
import '../../css/x/xt1fr6buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vvp3mvl2g"/><path class="zbfibgbbq"/><circle class="xt1fr6buf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:video-duotone" {...props}></Icon>
