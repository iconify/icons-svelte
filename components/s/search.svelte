<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gnzekqbpq.css';
import '../../css/m/m4w0vq-oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":32};
const content = `<g class="cuyn6tgcc"><path class="gnzekqbpq"/><path class="m4w0vq-oc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:search" {...props}></Icon>
