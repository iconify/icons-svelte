<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpn187_zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpn187_zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shopify-light" {...props}></Icon>
