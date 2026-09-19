<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eq44zu3zv.css';
import '../../css/k/k2jkv656h.css';
import '../../css/f/f2vk32anf.css';
import '../../css/h/hfinebcgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="eq44zu3zv"/><path class="k2jkv656h"/><path class="f2vk32anf"/><path class="hfinebcgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shopping-mall" {...props}></Icon>
