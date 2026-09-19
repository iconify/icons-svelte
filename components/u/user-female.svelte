<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5_nc9h-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5_nc9h-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:user-female" {...props}></Icon>
