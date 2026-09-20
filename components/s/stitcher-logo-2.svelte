<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhhfrzbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhhfrzbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stitcher-logo-2" {...props}></Icon>
