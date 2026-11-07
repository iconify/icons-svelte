<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/r/rmixrvbhu.css';
import '../../css/e/et9k69bbo.css';
import '../../css/p/p9t5yfbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="rmixrvbhu"/><path class="et9k69bbo"/><path class="p9t5yfbwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-minimalistic-broken" {...props}></Icon>
