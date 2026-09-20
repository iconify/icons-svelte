<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf8p8nt7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sf8p8nt7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:view-vertical" {...props}></Icon>
