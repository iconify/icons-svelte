<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf5ad9bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="sf5ad9bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-11" {...props}></Icon>
