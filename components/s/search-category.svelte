<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybh2h7nyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ybh2h7nyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:search-category" {...props}></Icon>
