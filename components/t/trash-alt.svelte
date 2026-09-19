<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfucfob_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yfucfob_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:trash-alt" {...props}></Icon>
