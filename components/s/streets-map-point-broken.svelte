<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ijmauiszs.css';
import '../../css/q/qgn5of9bp.css';
import '../../css/k/k-xqiwbqo.css';
import '../../css/z/zwiw2-bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ijmauiszs"/><path class="qgn5of9bp"/><path class="k-xqiwbqo"/><path class="zwiw2-bkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-map-point-broken" {...props}></Icon>
