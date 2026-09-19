<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/vfa2ogh1h.css';
import '../../css/w/wle1ht-hp.css';
import '../../css/q/qvdirabnc.css';
import '../../css/s/smjgjkbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="vfa2ogh1h"/><path class="wle1ht-hp"/><path class="qvdirabnc"/><path class="smjgjkbdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:tl" {...props}></Icon>
