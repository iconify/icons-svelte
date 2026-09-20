<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ragzbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0ragzbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:unlink-filled" {...props}></Icon>
