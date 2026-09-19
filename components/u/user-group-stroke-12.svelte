<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/aqce0abzy.css';
import '../../css/u/uc71xy3ii.css';
import '../../css/t/td0om22as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="aqce0abzy"/><circle class="uc71xy3ii"/><path class="td0om22as"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-group-stroke-12" {...props}></Icon>
