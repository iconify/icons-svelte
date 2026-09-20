<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4c6lqbbt.css';
import '../../css/c/cvtxclbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4c6lqbbt"/><path class="cvtxclbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:stats-line-graph-circle" {...props}></Icon>
