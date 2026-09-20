<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc9v1m4ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nc9v1m4ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-gas-flame" {...props}></Icon>
