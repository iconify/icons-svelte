<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3of49b8y.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eimxpcxbf.css';
import '../../css/k/kokokn3dg.css';
import '../../css/z/zs5u1v-qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x3of49b8y"/><g class="dt0cm9dhy primary"><path class="eimxpcxbf"/><path class="kokokn3dg"/><path class="zs5u1v-qk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:warehouse-duo" {...props}></Icon>
