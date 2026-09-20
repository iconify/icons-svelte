<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlui4r1hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlui4r1hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shining-line" {...props}></Icon>
