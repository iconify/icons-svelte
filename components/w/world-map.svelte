<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/azwq7yrxv.css';
import '../../css/s/s-bi71b0s.css';
import '../../css/m/m7fbntb7q.css';
import '../../css/z/z7va8o1ys.css';
import '../../css/h/h-ow21b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="azwq7yrxv"/><path class="s-bi71b0s"/><path class="m7fbntb7q"/><path class="z7va8o1ys"/><path class="h-ow21b9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:world-map" {...props}></Icon>
