<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o_onwfy1m.css';
import '../../css/s/sfxgh6bez.css';
import '../../css/d/d8f9mr75j.css';
import '../../css/q/qgimfw8xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><path class="sfxgh6bez"/><path class="d8f9mr75j"/><path class="qgimfw8xw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-broken" {...props}></Icon>
