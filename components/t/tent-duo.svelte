<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fxpjof0ho.css';
import '../../css/k/koqkggbqh.css';
import '../../css/x/xlau4cdnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fxpjof0ho"/><path class="koqkggbqh wm-a"/><path class="xlau4cdnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tent-duo" {...props}></Icon>
