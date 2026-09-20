<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1b5zwbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e1b5zwbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:viadeo-square" {...props}></Icon>
