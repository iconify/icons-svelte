<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u9u89mb-h.css';
import '../../css/n/n-8nhbbnb.css';
import '../../css/y/yoy8e1bnl.css';
import '../../css/t/tk77rcb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u9u89mb-h"/><path class="n-8nhbbnb"/><path class="yoy8e1bnl"/><path class="tk77rcb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-top-to-bottom-broken" {...props}></Icon>
