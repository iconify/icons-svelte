<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzv9pj7uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzv9pj7uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:slideshow" {...props}></Icon>
