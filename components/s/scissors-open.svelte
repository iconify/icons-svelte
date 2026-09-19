<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y7iziobxo.css';
import '../../css/v/vkjczyb4h.css';
import '../../css/j/jln9ezbnx.css';
import '../../css/h/h1boidc1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y7iziobxo"/><path class="vkjczyb4h"/><path clip-rule="evenodd" class="jln9ezbnx"/><path class="h1boidc1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:scissors-open" {...props}></Icon>
