<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfu1nsbti.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cu6lg7pxc.css';
import '../../css/t/tapbstm2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfu1nsbti secondary"/><g class="dt0cm9dhy primary"><path class="cu6lg7pxc"/><path class="tapbstm2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ruler-duo" {...props}></Icon>
