<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fkijn4jux.css';
import '../../css/d/dppta002c.css';
import '../../css/w/wr28_ubwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fkijn4jux"/><path class="dppta002c"/><path class="wr28_ubwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-lock-minus-02" {...props}></Icon>
