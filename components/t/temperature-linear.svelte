<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mzuq4x0dn.css';
import '../../css/k/ktz4j74-r.css';
import '../../css/w/w29ath28m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mzuq4x0dn"/><path class="ktz4j74-r"/><path class="w29ath28m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:temperature-linear" {...props}></Icon>
