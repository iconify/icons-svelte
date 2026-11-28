<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n3heq6b6w.css';
import '../../css/i/ip-lweb_e.css';
import '../../css/j/jmt_hp8qh.css';
import '../../css/q/qj4rgrb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n3heq6b6w"/><path class="ip-lweb_e"/><path class="jmt_hp8qh"/><path class="qj4rgrb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:teacher" {...props}></Icon>
