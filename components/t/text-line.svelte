<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrct9ezjq.css';
import '../../css/k/k9gvrkmhy.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 mrct9ezjq"/><path class="clr-i-outline clr-i-outline-path-2 k9gvrkmhy"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:text-line" {...props}></Icon>
