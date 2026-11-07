<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ng9n0mb9m.css';
import '../../css/t/twwb0_bxq.css';
import '../../css/g/gdul00bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ng9n0mb9m"/><path class="twwb0_bxq"/><path class="gdul00bkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-loud-line-duotone" {...props}></Icon>
