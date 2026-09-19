<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx8nzig8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dx8nzig8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tree-view-alt" {...props}></Icon>
