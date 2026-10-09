<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anemfwqgt.css';
import '../../css/k/ke851bcgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="anemfwqgt"/><path class="ke851bcgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-asc-20-bold" {...props}></Icon>
