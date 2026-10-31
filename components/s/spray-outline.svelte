<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s9rkou0mf.css';
import '../../css/m/m_ogqzi-d.css';
import '../../css/v/vjc3f2jdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s9rkou0mf"/><path class="m_ogqzi-d"/><path clip-rule="evenodd" class="vjc3f2jdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:spray-outline" {...props}></Icon>
