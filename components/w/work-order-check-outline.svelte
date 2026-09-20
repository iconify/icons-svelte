<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3qj_ibrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o3qj_ibrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-check-outline" {...props}></Icon>
