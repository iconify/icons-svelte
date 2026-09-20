<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1e0vbssl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j1e0vbssl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:server" {...props}></Icon>
