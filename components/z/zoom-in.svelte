<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6cgkubqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w6cgkubqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:zoom-in" {...props}></Icon>
