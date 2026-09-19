<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl-8y1hvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tl-8y1hvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shield-cat" {...props}></Icon>
