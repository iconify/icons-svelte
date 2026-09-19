<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usagr9buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="usagr9buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarev" {...props}></Icon>
