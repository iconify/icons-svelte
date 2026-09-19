<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzuimr-to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lzuimr-to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:windows" {...props}></Icon>
