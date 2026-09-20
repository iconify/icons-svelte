<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l12u5k3ye.css';
import '../../css/i/ibs-b3bnk.css';
import '../../css/u/un073yd9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l12u5k3ye"/><path class="ibs-b3bnk"/><path clip-rule="evenodd" class="un073yd9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:special-effects-outline" {...props}></Icon>
