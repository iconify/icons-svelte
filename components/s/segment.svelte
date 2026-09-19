<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c_a_osb6t.css';
import '../../css/w/w8wnakb3s.css';
import '../../css/z/z4ubyo-3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_a_osb6t"/><path class="w8wnakb3s"/><path class="z4ubyo-3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:segment" {...props}></Icon>
