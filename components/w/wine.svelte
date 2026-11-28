<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q6fepbcme.css';
import '../../css/s/sy986tb5k.css';
import '../../css/w/wrum7db2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q6fepbcme"/><path class="sy986tb5k"/><path class="wrum7db2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wine" {...props}></Icon>
