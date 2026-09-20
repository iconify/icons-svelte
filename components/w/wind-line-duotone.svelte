<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o9eziwahb.css';
import '../../css/u/uhyb91t7h.css';
import '../../css/e/e1amrgqjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9eziwahb"/><path class="uhyb91t7h"/><path class="e1amrgqjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wind-line-duotone" {...props}></Icon>
