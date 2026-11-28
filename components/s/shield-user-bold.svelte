<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5edy9lin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i5edy9lin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-user-bold" {...props}></Icon>
