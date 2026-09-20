<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pq3gn9qof.css';
import '../../css/k/ksqk5bc1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pq3gn9qof"/><path class="ksqk5bc1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:settings" {...props}></Icon>
