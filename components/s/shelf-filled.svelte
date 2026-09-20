<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-9_s5i_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z-9_s5i_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shelf-filled" {...props}></Icon>
