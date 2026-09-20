<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf61b5bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf61b5bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:utensils-alt" {...props}></Icon>
