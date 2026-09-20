<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5et9lxjq.css';
import '../../css/i/i8m-zjguk.css';
import '../../css/i/irczjwbis.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/g/gx26emb1z.css';
import '../../css/z/zg9uhs63y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m5et9lxjq"/><path class="i8m-zjguk"/><path class="irczjwbis"/><g class="jn8qy4bru"><path class="gx26emb1z"/><path class="zg9uhs63y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wood" {...props}></Icon>
