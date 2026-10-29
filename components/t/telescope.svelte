<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kbj8nvb7i.css';
import '../../css/p/ptk50absq.css';
import '../../css/n/nboiatbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kbj8nvb7i"/><path class="ptk50absq"/><path class="nboiatbai wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:telescope" {...props}></Icon>
