<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpty2brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rfpty2brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:signal" {...props}></Icon>
