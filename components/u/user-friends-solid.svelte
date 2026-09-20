<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_lzigb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_lzigb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-friends-solid" {...props}></Icon>
