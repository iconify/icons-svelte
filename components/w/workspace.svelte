<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fybd5wb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fybd5wb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:workspace" {...props}></Icon>
