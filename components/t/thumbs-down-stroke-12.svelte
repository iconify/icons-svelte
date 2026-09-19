<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/jjx2uec9c.css';
import '../../css/s/suo1febzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="jjx2uec9c"/><rect class="suo1febzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-down-stroke-12" {...props}></Icon>
