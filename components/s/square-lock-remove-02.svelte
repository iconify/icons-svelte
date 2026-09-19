<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tcabn2byh.css';
import '../../css/d/dppta002c.css';
import '../../css/w/wr28_ubwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tcabn2byh"/><path class="dppta002c"/><path class="wr28_ubwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-lock-remove-02" {...props}></Icon>
