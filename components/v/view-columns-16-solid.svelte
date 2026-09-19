<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksonub4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lksonub4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:view-columns-16-solid" {...props}></Icon>
