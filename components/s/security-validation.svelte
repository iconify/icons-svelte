<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qlu0ufjal.css';
import '../../css/s/sb7awif1l.css';
import '../../css/u/uebd-hbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qlu0ufjal"/><path class="sb7awif1l"/><path class="uebd-hbog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:security-validation" {...props}></Icon>
