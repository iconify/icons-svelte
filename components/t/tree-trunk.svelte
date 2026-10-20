<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh9bfhbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eh9bfhbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tree-trunk" {...props}></Icon>
