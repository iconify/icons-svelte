<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc0qmpbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gc0qmpbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:triangle-left" {...props}></Icon>
