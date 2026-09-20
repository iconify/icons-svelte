<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkibg5b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qkibg5b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-manual-filled" {...props}></Icon>
