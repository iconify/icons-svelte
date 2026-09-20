<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rcp39sbqz.css';
import '../../css/q/qkpxkebkm.css';
import '../../css/u/u1_3hst1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rcp39sbqz"/><path class="qkpxkebkm"/><path class="u1_3hst1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:watch-circle-time-flat" {...props}></Icon>
