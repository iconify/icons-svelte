<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i0xak7bzd.css';
import '../../css/v/vqpagmb7q.css';
import '../../css/g/gzmbm5zua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect vector-effect="non-scaling-stroke" class="i0xak7bzd"/><rect vector-effect="non-scaling-stroke" class="vqpagmb7q"/><rect vector-effect="non-scaling-stroke" class="gzmbm5zua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:sites" {...props}></Icon>
