<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9rf3d8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py9rf3d8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:text-image-left" {...props}></Icon>
