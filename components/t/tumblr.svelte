<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znvomhwkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":488};
const content = `<path class="znvomhwkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:tumblr" {...props}></Icon>
