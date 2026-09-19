<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2r0fbbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":709};
const content = `<path class="r2r0fbbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:wrench" {...props}></Icon>
