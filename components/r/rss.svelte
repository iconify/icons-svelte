<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ro0_byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k5ro0_byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rss" {...props}></Icon>
