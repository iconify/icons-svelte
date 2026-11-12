<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxjnv6btj.css';
import '../../css/o/o78-gg1um.css';
import '../../css/m/mam2srhpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxjnv6btj"/><path class="o78-gg1um"/><path class="mam2srhpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taiga-light" {...props}></Icon>
