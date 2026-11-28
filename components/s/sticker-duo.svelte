<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-drp5bju.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s3aa3b7qt.css';
import '../../css/s/s0rcl214k.css';
import '../../css/d/dmnr1ibmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-drp5bju secondary"/><g class="dt0cm9dhy primary"><path class="s3aa3b7qt"/><path class="s0rcl214k"/><path class="dmnr1ibmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sticker-duo" {...props}></Icon>
