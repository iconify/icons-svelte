<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/u/ujn2e1bud.css';
import '../../css/w/wv_civb5p.css';
import '../../css/s/sp_jcmb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7mrcgb5f"/><path class="ujn2e1bud"/><path class="wv_civb5p"/><path class="sp_jcmb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-broken" {...props}></Icon>
