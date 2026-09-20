<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1qq4vblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h1qq4vblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vomiting-face-in-circle-outline" {...props}></Icon>
