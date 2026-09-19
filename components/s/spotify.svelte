<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aslbnps4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="aslbnps4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:spotify" {...props}></Icon>
