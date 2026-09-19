<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/z/zb0q9-bfp.css';
import '../../css/o/ol5nzqv4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="zb0q9-bfp"/><path class="ol5nzqv4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-list-stroke-12" {...props}></Icon>
