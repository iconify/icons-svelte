<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/s/syvs5h-jc.css';
import '../../css/j/ji0ebbb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="syvs5h-jc"/><path class="ji0ebbb0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:vest-2" {...props}></Icon>
