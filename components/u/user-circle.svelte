<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnm3uwu-x.css';
import '../../css/w/wwvjbde6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gnm3uwu-x"/><path class="wwvjbde6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:user-circle" {...props}></Icon>
