<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg9qj7zwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pg9qj7zwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tree-with-leaf-bottom-right-horizontal-line" {...props}></Icon>
