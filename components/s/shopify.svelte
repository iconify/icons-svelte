<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma39zmb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":452,"height":512};
const content = `<path class="ma39zmb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shopify" {...props}></Icon>
