<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf1ycbcru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yf1ycbcru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:tag" {...props}></Icon>
