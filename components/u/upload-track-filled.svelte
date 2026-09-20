<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y479ucc5d.css';
import '../../css/a/ax13qlbtc.css';
import '../../css/k/kmwrnkbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y479ucc5d"/><path class="ax13qlbtc"/><path clip-rule="evenodd" class="kmwrnkbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:upload-track-filled" {...props}></Icon>
