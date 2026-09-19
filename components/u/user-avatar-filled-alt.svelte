<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sulruw6qc.css';
import '../../css/g/glr1ycbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sulruw6qc"/><path class="glr1ycbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-avatar-filled-alt" {...props}></Icon>
