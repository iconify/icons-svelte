<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7qlfbcri.css';
import '../../css/q/qcjn5ubrr.css';
import '../../css/g/g_l_olm7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e7qlfbcri"/><path class="qcjn5ubrr"/><path clip-rule="evenodd" class="g_l_olm7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-appointment-filled" {...props}></Icon>
