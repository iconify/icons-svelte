<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt98u-vbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kt98u-vbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:septagon" {...props}></Icon>
