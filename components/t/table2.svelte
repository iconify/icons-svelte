<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb3xt4key.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pb3xt4key"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:table2" {...props}></Icon>
