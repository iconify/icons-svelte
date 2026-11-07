<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ojwywwbjm.css';
import '../../css/a/adqy_2bos.css';
import '../../css/m/mcmjfab3p.css';
import '../../css/n/ncb20ka2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ojwywwbjm"/><path class="adqy_2bos"/><path class="mcmjfab3p"/><path class="ncb20ka2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-2-broken" {...props}></Icon>
