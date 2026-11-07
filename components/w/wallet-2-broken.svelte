<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p9a5saclq.css';
import '../../css/i/ic59sq0-o.css';
import '../../css/a/a8ue-2cgj.css';
import '../../css/t/t2jvb6bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9a5saclq"/><path class="ic59sq0-o"/><path class="a8ue-2cgj"/><path class="t2jvb6bpe"/><path class="t2jvb6bpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-2-broken" {...props}></Icon>
