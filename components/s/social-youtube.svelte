<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aif_2qd2x.css';
import '../../css/j/jiz-qyxew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="aif_2qd2x"/><path class="jiz-qyxew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-youtube" {...props}></Icon>
