<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nacman8nc.css';
import '../../css/b/b_avhwbzz.css';
import '../../css/n/nho4eobhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nacman8nc"/><path class="b_avhwbzz"/><path class="nho4eobhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:webhook-duo" {...props}></Icon>
