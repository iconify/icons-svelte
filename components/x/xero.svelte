<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btg86dbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="btg86dbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:xero" {...props}></Icon>
