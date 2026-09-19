<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvutvv_bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pvutvv_bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stockup" {...props}></Icon>
