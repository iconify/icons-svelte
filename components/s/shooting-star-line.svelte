<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9v96drtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9v96drtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:shooting-star-line" {...props}></Icon>
