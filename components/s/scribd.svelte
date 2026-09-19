<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d64-tcb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":488};
const content = `<path class="d64-tcb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:scribd" {...props}></Icon>
