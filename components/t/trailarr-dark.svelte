<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnhbskd2a.css';
import '../../css/b/bnsgscc2v.css';
import '../../css/f/f2_b1ubxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnhbskd2a"/><path class="bnsgscc2v"/><path class="f2_b1ubxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trailarr-dark" {...props}></Icon>
