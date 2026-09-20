<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etphgj1if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="etphgj1if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-with-baht" {...props}></Icon>
