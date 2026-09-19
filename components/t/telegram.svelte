<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuy9-04as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zuy9-04as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:telegram" {...props}></Icon>
