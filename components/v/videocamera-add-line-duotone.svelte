<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ychitgsnk.css';
import '../../css/l/lennyzbya.css';
import '../../css/g/gokb5qbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ychitgsnk"/><path class="lennyzbya"/><path class="gokb5qbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-add-line-duotone" {...props}></Icon>
