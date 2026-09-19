<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/mp0vydb-q.css';
import '../../css/j/j5knwxbsn.css';
import '../../css/v/vw0y74bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="mp0vydb-q"/><path class="j5knwxbsn"/><path class="vw0y74bfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wrench-02" {...props}></Icon>
