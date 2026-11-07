<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/b/bcjcfx97b.css';
import '../../css/d/dkl7vo9ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7mrcgb5f"/><path class="bcjcfx97b"/><path class="dkl7vo9ud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-linear" {...props}></Icon>
