<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrcnysbjv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/u/us5t91bal.css';
import '../../css/n/n7suyab1r.css';
import '../../css/s/s3_m7j74z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrcnysbjv secondary"/><g class="dt0cm9dhy primary"><path class="e77ebfb5e"/><path class="us5t91bal"/><path class="n7suyab1r"/><path class="s3_m7j74z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-pi-duo" {...props}></Icon>
