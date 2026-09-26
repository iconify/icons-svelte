<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l_z2a8vzi.css';
import '../../css/j/jjar52fez.css';
import '../../css/j/jxnmi_jhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="l_z2a8vzi"/><path class="jjar52fez"/><path class="jxnmi_jhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-check-line-duotone" {...props}></Icon>
