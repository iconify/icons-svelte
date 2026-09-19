<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-b92b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ey-b92b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:share-sharp" {...props}></Icon>
