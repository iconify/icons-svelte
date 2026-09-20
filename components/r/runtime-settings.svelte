<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1m7o-bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d1m7o-bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:runtime-settings" {...props}></Icon>
