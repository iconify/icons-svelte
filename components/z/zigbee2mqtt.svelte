<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l974u_srj.css';
import '../../css/h/hh0j4fnrz.css';
import '../../css/e/eddw_qbni.css';
import '../../css/n/n_f6npbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l974u_srj"/><path class="hh0j4fnrz"/><path class="eddw_qbni"/><path class="n_f6npbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zigbee2mqtt" {...props}></Icon>
