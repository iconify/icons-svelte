<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj8u-yb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj8u-yb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:squares-exclude" {...props}></Icon>
