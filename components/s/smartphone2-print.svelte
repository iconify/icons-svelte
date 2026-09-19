<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xo2h4kz3i.css';
import '../../css/a/adtlylf5k.css';
import '../../css/x/x489igpny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xo2h4kz3i"/><path clip-rule="evenodd" class="adtlylf5k"/><path class="x489igpny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:smartphone2-print" {...props}></Icon>
