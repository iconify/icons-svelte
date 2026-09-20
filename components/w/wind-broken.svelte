<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g5i18qe1o.css';
import '../../css/c/ca0i9ubof.css';
import '../../css/v/vrm2ribsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g5i18qe1o"/><path class="ca0i9ubof"/><path class="vrm2ribsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wind-broken" {...props}></Icon>
