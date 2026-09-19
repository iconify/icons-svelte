<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3trzrbdm.css';
import '../../css/l/lrflrndpo.css';
import '../../css/d/dm5bfnbry.css';
import '../../css/m/m_rznqb0n.css';
import '../../css/i/izcsuhbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3trzrbdm"/><circle class="lrflrndpo"/><circle class="dm5bfnbry"/><circle class="m_rznqb0n"/><path class="izcsuhbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speechbubble" {...props}></Icon>
