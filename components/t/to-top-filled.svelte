<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtxcc5b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wtxcc5b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:to-top-filled" {...props}></Icon>
