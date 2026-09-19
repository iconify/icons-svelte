<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xufc6zb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1025};
const content = `<path class="xufc6zb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sd" {...props}></Icon>
