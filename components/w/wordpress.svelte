<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guct1ybvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="guct1ybvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:wordpress" {...props}></Icon>
