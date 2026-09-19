<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_txeacgn.css';
import '../../css/s/sn58b5b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_txeacgn"/><path class="sn58b5b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wallet" {...props}></Icon>
