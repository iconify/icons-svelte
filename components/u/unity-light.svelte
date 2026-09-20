<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzifvdi3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":263};
const content = `<path class="xzifvdi3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unity-light" {...props}></Icon>
