<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylee5g30h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ylee5g30h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:top-right-outline" {...props}></Icon>
