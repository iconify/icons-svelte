<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_4p6yb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_4p6yb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner5" {...props}></Icon>
