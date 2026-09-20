<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv5_m0b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uv5_m0b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-management-settings" {...props}></Icon>
