<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4nh9cb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4nh9cb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-eye-line" {...props}></Icon>
