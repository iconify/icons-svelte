<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ncb20ka2n.css';
import '../../css/u/ujr860b1o.css';
import '../../css/a/adqy_2bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ncb20ka2n"/><path class="ujr860b1o"/><path class="adqy_2bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-linear" {...props}></Icon>
