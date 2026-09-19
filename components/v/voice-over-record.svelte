<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhets1rsz.css';
import '../../css/z/zl5kt1bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhets1rsz"/><path class="zl5kt1bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:voice-over-record" {...props}></Icon>
