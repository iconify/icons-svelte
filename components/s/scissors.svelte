<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ficsvcctd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ficsvcctd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:scissors" {...props}></Icon>
