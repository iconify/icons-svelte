<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4w_49bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i4w_49bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vials" {...props}></Icon>
