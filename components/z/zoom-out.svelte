<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvsdd0eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gwvsdd0eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:zoom-out" {...props}></Icon>
