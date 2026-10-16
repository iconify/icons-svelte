<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjnvkbuz.css';
import '../../css/d/drtg3332s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="drtg3332s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wholesale-price-48" {...props}></Icon>
