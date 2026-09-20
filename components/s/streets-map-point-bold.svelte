<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c7q7eibda.css';
import '../../css/v/vfmylgypt.css';
import '../../css/y/ynh320vat.css';
import '../../css/b/ba5x8cdcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c7q7eibda"/><path class="vfmylgypt"/><path clip-rule="evenodd" class="ynh320vat"/><path class="ba5x8cdcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-map-point-bold" {...props}></Icon>
