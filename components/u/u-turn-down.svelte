<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vq3pbhbzo.css';
import '../../css/u/u_erkqblh.css';
import '../../css/v/vo8z19zmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vq3pbhbzo"/><path class="u_erkqblh"/><circle transform="rotate(90 35 39)" class="vo8z19zmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:u-turn-down" {...props}></Icon>
