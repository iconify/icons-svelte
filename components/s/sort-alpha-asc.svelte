<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_840f2vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="x_840f2vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sort-alpha-asc" {...props}></Icon>
