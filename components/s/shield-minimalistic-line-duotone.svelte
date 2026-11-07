<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k_9yvrb1q.css';
import '../../css/j/jtnup6gsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k_9yvrb1q"/><path class="jtnup6gsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-line-duotone" {...props}></Icon>
