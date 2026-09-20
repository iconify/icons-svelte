<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/oh053ab4q.css';
import '../../css/w/wl1f6ubih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="oh053ab4q"/><path class="wl1f6ubih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:strawberry" {...props}></Icon>
