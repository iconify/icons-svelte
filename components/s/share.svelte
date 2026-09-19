<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9f2b9-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc9f2b9-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:share" {...props}></Icon>
