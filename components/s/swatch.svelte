<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za3khxbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za3khxbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:swatch" {...props}></Icon>
