<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d0wxiwb3z.css';
import '../../css/q/qgbomkeqp.css';
import '../../css/f/fml2qzxuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d0wxiwb3z"/><path class="qgbomkeqp"/><path class="fml2qzxuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-broken" {...props}></Icon>
