<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfj6s_bbb.css';
import '../../css/w/wsi6v13mq.css';
import '../../css/h/h_1tt7l9g.css';
import '../../css/p/pfrpmpb1c.css';
import '../../css/n/nul8knx4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xfj6s_bbb"/><path class="wsi6v13mq"/><path class="h_1tt7l9g"/><path class="pfrpmpb1c"/><path class="nul8knx4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wiki-js-dark" {...props}></Icon>
