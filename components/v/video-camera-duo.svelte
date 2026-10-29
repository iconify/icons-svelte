<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bo1uwgbfy.css';
import '../../css/v/vfx376v4r.css';
import '../../css/r/rcb7clbki.css';
import '../../css/z/za3dt0bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bo1uwgbfy"/><path class="vfx376v4r wm-a"/><path class="rcb7clbki wm-a"/><path class="za3dt0bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-camera-duo" {...props}></Icon>
