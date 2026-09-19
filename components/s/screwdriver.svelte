<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4gul0b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4gul0b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:screwdriver" {...props}></Icon>
