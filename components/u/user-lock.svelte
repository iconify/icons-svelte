<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr2dbacrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rr2dbacrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-lock" {...props}></Icon>
