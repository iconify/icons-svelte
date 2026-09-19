<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsel27bbh.css';
import '../../css/x/xqhescv-e.css';
import '../../css/i/im33libln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rsel27bbh"><path class="xqhescv-e"/><path class="im33libln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vigo" {...props}></Icon>
