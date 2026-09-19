<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnu-9ccgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gnu-9ccgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:vps" {...props}></Icon>
