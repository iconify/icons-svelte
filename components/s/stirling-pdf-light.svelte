<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmrg6hbwc.css';
import '../../css/h/h7oxz0boa.css';
import '../../css/p/pvcco7a8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmrg6hbwc"/><path class="h7oxz0boa"/><path class="pvcco7a8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stirling-pdf-light" {...props}></Icon>
