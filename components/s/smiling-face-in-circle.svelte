<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx7y6ebae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qx7y6ebae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smiling-face-in-circle" {...props}></Icon>
