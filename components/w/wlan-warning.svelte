<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk9_w01ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bk9_w01ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:wlan-warning" {...props}></Icon>
