<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rheme10ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rheme10ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:sticker-mule" {...props}></Icon>
