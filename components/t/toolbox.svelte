<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fdqlhjbof.css';
import '../../css/m/mpqzm5b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="fdqlhjbof"/><path class="mpqzm5b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:toolbox" {...props}></Icon>
