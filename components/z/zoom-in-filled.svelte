<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr_q1qn4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wr_q1qn4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:zoom-in-filled" {...props}></Icon>
