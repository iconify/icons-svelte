<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g32d_5bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g32d_5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-whatsapp" {...props}></Icon>
