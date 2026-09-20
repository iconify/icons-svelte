<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkys025md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkys025md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wrench" {...props}></Icon>
