<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwda_o2io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwda_o2io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:row-height-m-filled" {...props}></Icon>
