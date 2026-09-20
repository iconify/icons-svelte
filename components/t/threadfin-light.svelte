<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xus3r2plp.css';
import '../../css/o/orv7ykb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xus3r2plp"/><path class="orv7ykb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threadfin-light" {...props}></Icon>
