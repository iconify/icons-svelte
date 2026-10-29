<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kxan-_bmm.css';
import '../../css/a/aacc-9bme.css';
import '../../css/n/nvu86dbph.css';
import '../../css/d/dpw0_4bhq.css';
import '../../css/z/zfrxwsb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kxan-_bmm"/><path class="aacc-9bme wm-k"/><path class="nvu86dbph wm-a"/><path class="dpw0_4bhq wm-k"/><path class="wm-a zfrxwsb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-plus-sketch" {...props}></Icon>
