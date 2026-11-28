<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd0nb5o5d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j3k84q9hw.css';
import '../../css/b/bjqhmrb9b.css';
import '../../css/p/plnv7b-ws.css';
import '../../css/j/j3eweebcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd0nb5o5d secondary"/><g class="dt0cm9dhy primary"><path class="j3k84q9hw"/><path class="bjqhmrb9b"/><path class="plnv7b-ws"/><path class="j3eweebcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tulip-duo" {...props}></Icon>
