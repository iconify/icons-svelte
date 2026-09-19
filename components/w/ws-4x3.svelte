<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/d/dbwss0bxe.css';
import '../../css/m/mtrh8qv2q.css';
import '../../css/q/qtudwnmhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="dbwss0bxe"/><path class="mtrh8qv2q"/><path class="qtudwnmhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ws-4x3" {...props}></Icon>
