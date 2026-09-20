<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b581idbbf.css';
import '../../css/e/epme-tb1k.css';
import '../../css/i/iar3qwbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b581idbbf"/><path class="epme-tb1k"/><path class="iar3qwbrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-price-broken" {...props}></Icon>
