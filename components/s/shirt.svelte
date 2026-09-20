<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mt6snqu5h.css';
import '../../css/f/f5ppuo7gp.css';
import '../../css/m/mc3zo1mlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mt6snqu5h"/><path class="f5ppuo7gp"/><path class="mc3zo1mlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:shirt" {...props}></Icon>
