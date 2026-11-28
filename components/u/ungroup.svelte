<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-la7-bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i-la7-bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ungroup" {...props}></Icon>
