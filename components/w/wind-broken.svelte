<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gt-b8gb9l.css';
import '../../css/i/ige762y5f.css';
import '../../css/h/hl1uepbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gt-b8gb9l"/><path class="ige762y5f"/><path class="hl1uepbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wind-broken" {...props}></Icon>
