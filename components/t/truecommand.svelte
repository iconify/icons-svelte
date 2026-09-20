<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmpngjpsi.css';
import '../../css/q/qzvdi8qaf.css';
import '../../css/x/xi_w0vrbe.css';
import '../../css/n/n5wctwmmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vmpngjpsi"/><path class="qzvdi8qaf"/><path class="xi_w0vrbe"/><path class="n5wctwmmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:truecommand" {...props}></Icon>
