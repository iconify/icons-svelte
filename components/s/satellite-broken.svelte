<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p82yzhump.css';
import '../../css/e/efyt3acxm.css';
import '../../css/l/l1vnaybdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p82yzhump"/><path class="efyt3acxm"/><path class="l1vnaybdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:satellite-broken" {...props}></Icon>
