<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imw1e3big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="imw1e3big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:tongue" {...props}></Icon>
