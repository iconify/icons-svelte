<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_-4vlmxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w_-4vlmxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shift-filled" {...props}></Icon>
