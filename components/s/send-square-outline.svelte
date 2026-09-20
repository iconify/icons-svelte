<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/esbwh55ly.css';
import '../../css/t/t99s0f6ww.css';
import '../../css/z/zuqh_gv5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="esbwh55ly"/><path class="t99s0f6ww"/><path clip-rule="evenodd" class="zuqh_gv5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:send-square-outline" {...props}></Icon>
