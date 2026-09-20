<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qgtd8187v.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/f/fbtujzbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qgtd8187v"/><path class="u7mrcgb5f"/><path class="fbtujzbta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-line-duotone" {...props}></Icon>
