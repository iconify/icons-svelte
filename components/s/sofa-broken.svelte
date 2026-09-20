<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aiu2dac3q.css';
import '../../css/k/kpcjxbbzl.css';
import '../../css/n/ncb20ka2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aiu2dac3q"/><path class="kpcjxbbzl"/><path class="ncb20ka2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-broken" {...props}></Icon>
