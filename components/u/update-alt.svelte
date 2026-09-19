<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-pmcc75q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k-pmcc75q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:update-alt" {...props}></Icon>
