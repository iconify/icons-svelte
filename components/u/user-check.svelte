<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx77dvllf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kx77dvllf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-check" {...props}></Icon>
