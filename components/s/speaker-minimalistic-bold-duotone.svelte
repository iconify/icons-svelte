<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sng0m5e4g.css';
import '../../css/e/emnqjpbpk.css';
import '../../css/m/m8jecfmey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sng0m5e4g"/><path class="emnqjpbpk"/><path clip-rule="evenodd" class="m8jecfmey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speaker-minimalistic-bold-duotone" {...props}></Icon>
