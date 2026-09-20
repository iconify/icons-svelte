<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9kxl12hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k9kxl12hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dots-up-down" {...props}></Icon>
