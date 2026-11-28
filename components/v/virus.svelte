<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xqunm-tmm.css';
import '../../css/x/xyzpfmoeg.css';
import '../../css/f/flre5izaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xqunm-tmm"/><path class="xyzpfmoeg"/><path class="flre5izaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:virus" {...props}></Icon>
