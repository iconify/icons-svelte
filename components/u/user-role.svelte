<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e61f3ybjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e61f3ybjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-role" {...props}></Icon>
