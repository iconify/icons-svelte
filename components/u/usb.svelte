<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay-_lhcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ay-_lhcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:usb" {...props}></Icon>
