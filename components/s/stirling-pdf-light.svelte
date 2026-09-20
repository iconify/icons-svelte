<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmrg6hbwc.css';
import '../../css/u/u8nonlcqn.css';
import '../../css/p/pvcco7a8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmrg6hbwc"/><path class="u8nonlcqn"/><path class="pvcco7a8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stirling-pdf-light" {...props}></Icon>
