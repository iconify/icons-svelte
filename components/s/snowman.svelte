<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fkgs8cb4p.css';
import '../../css/l/lyesv9buc.css';
import '../../css/t/t_b2msbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="fkgs8cb4p"/><path class="lyesv9buc"/><path class="t_b2msbub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:snowman" {...props}></Icon>
