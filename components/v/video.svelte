<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0o9u5blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0o9u5blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:video" {...props}></Icon>
