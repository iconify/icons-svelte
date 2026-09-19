<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zstbz94ff.css';
import '../../css/e/ep6g36qhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="zstbz94ff"/><path class="ep6g36qhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:search-stroke-16" {...props}></Icon>
