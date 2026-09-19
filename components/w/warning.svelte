<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ukdd74j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_ukdd74j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:warning" {...props}></Icon>
