<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/za3dt0bho.css';
import '../../css/r/rcb7clbki.css';
import '../../css/k/k-k6k285a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="za3dt0bho"/><path class="rcb7clbki wm-a"/><path class="k-k6k285a wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-plus" {...props}></Icon>
