<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tzt0_bt_l.css';
import '../../css/k/kls3_nbwn.css';
import '../../css/d/d-l22-bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="tzt0_bt_l"/><path class="kls3_nbwn"/><path class="d-l22-bpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:tent-banner" {...props}></Icon>
