<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l0_d9_beu.css';
import '../../css/p/pq4u4ksec.css';
import '../../css/j/jr5oamekb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l0_d9_beu"/><path class="pq4u4ksec"/><path class="jr5oamekb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shankh" {...props}></Icon>
