<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l639ivboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l639ivboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-overflow-fill" {...props}></Icon>
