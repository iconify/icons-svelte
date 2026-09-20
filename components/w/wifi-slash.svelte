<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv4fwl-ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv4fwl-ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wifi-slash" {...props}></Icon>
