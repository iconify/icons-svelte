<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqd6qpbht.css';
import '../../css/b/bbpo9lb1d.css';
import '../../css/p/pe1khgbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqd6qpbht"/><path class="bbpo9lb1d"/><path class="pe1khgbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:vibrationmode" {...props}></Icon>
