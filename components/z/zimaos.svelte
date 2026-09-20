<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ere8b8b-s.css';
import '../../css/s/su2ci-bpz.css';
import '../../css/q/qyvbf9bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ere8b8b-s"/><path class="su2ci-bpz"/><path class="qyvbf9bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zimaos" {...props}></Icon>
