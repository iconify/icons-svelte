<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5kz7ap7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x5kz7ap7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:subtitle-filled" {...props}></Icon>
