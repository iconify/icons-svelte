<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fz4g6ybxa.css';
import '../../css/g/gvilvubwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40,"left":12,"top":12};
const content = `<g class="ft5dv1b6b"><path class="fz4g6ybxa"/><path class="gvilvubwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:workday" {...props}></Icon>
