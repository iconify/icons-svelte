<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmtjz3qxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmtjz3qxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points" {...props}></Icon>
