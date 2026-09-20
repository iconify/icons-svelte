<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6448q3ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6448q3ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:value-none" {...props}></Icon>
