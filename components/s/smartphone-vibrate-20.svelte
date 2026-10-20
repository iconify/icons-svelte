<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d90wrwq5c.css';
import '../../css/z/z-2w2eb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d90wrwq5c"/><path class="z-2w2eb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-vibrate-20" {...props}></Icon>
