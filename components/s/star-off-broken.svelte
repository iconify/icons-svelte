<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a_v4sl8xe.css';
import '../../css/c/c4kuzacnf.css';
import '../../css/g/gvam3ngsc.css';
import '../../css/m/m87x8mmiu.css';
import '../../css/b/bari53b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a_v4sl8xe"/><path class="c4kuzacnf"/><path class="gvam3ngsc"/><path class="m87x8mmiu"/><path class="bari53b2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-off-broken" {...props}></Icon>
