<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m2olt1beo.css';
import '../../css/d/dab4yko7u.css';
import '../../css/f/fkqe7rzrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m2olt1beo"/><path clip-rule="evenodd" class="dab4yko7u"/><path class="fkqe7rzrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server-square-duotone" {...props}></Icon>
