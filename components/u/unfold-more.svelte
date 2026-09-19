<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfwc8-bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfwc8-bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:unfold-more" {...props}></Icon>
