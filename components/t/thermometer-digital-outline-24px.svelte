<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/ju7b3cb4d.css';
import '../../css/t/tc-ist7-g.css';
import '../../css/s/slqajwrnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ju7b3cb4d"/><path clip-rule="evenodd" class="tc-ist7-g"/><path class="slqajwrnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:thermometer-digital-outline-24px" {...props}></Icon>
