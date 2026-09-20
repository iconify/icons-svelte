<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nz-6xxb2y.css';
import '../../css/e/ec8_5vbia.css';
import '../../css/s/sog0659hq.css';
import '../../css/s/se_om3jvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nz-6xxb2y"/><path class="ec8_5vbia"/><path class="sog0659hq"/><path clip-rule="evenodd" class="se_om3jvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-cross-circle-outline" {...props}></Icon>
