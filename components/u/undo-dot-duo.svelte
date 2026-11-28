<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms6brvbow.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zr9i61kva.css';
import '../../css/r/rqp586bnn.css';
import '../../css/b/blvo7kblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms6brvbow secondary"/><g class="dt0cm9dhy primary"><path class="zr9i61kva"/><path class="rqp586bnn"/><path class="blvo7kblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:undo-dot-duo" {...props}></Icon>
