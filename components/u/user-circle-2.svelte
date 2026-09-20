<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/s/sj_zfbclt.css';
import '../../css/v/vl7c_o-va.css';
import '../../css/w/wky5h3byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="sj_zfbclt"/><path class="vl7c_o-va"/><path class="wky5h3byu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:user-circle-2" {...props}></Icon>
