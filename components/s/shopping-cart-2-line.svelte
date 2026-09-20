<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4l3vs4aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4l3vs4aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-cart-2-line" {...props}></Icon>
