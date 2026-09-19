<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_8tfcbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_8tfcbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tablet-portrait-sharp" {...props}></Icon>
