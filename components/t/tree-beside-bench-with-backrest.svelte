<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1r1dsu7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x1r1dsu7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tree-beside-bench-with-backrest" {...props}></Icon>
