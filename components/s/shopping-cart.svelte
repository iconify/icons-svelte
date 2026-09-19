<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0-a0abty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b0-a0abty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:shopping-cart" {...props}></Icon>
