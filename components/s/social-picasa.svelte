<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byywln2tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="byywln2tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-picasa" {...props}></Icon>
