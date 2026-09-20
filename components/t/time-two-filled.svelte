<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0bnbwbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l0bnbwbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:time-two-filled" {...props}></Icon>
