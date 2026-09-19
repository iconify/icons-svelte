<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tftwdrbwv.css';
import '../../css/m/mcue2tcqv.css';
import '../../css/o/ot1i2cc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tftwdrbwv"/><path class="mcue2tcqv"/><path class="ot1i2cc-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:time-management-circle" {...props}></Icon>
