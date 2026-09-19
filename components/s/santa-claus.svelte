<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ew36xlbmo.css';
import '../../css/d/dk5h7lbfd.css';
import '../../css/l/lgvo6lbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ew36xlbmo"/><path class="dk5h7lbfd"/><path class="lgvo6lbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:santa-claus" {...props}></Icon>
