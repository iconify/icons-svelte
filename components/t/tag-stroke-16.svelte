<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8rmcuiam.css';
import '../../css/j/jy4g_db5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a8rmcuiam"/><circle class="jy4g_db5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tag-stroke-16" {...props}></Icon>
